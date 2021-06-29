FROM node:14.1.0-alpine

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo

WORKDIR /app

RUN apk update && \
    npm install -g npm && \
    npm install -g @vue/cli && \
    npm install -g @vue/cli-init && \
    npm install -g create-nuxt-app
