FROM node:16-alpine3.13
COPY . /usr/src/web
WORKDIR /usr/src/web
EXPOSE 3000
RUN yarn
CMD ["yarn", "dev"]
