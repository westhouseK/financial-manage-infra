FROM node:14.1.0-alpine

ENV LANG C.UTF-8
ENV TZ Asia/Tokyo
RUN apk update && \
    apk add bash && \
    npm install -g npm && \
    npm install -g @vue/cli && \
    npm install -g @vue/cli-init

WORKDIR /app

EXPOSE 3000
CMD ["npm", "run", "dev"]