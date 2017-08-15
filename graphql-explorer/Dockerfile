FROM mhart/alpine-node:latest
RUN apk add --no-cache git curl
RUN git clone https://github.com/mmaico/graphql-explorer.git
RUN cd /graphql-explorer && npm install && npm install webpack-dev-server && NODE_ENV=development npm start &

EXPOSE 8787