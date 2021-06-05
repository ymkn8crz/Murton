FROM node:14.1.0-alpine

WORKDIR /app

# nuxt動かすだけなら、@vue/cliとか@vue/cli-initはいらない??
RUN apk update && \
    npm install -g npm && \
    npm install -g @vue/cli && \
    npm install -g @vue/cli-init && \
    npm install -g create-nuxt-app

ENV HOST 0.0.0.0

CMD ["npm", "run", "dev"]