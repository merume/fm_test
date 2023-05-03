FROM node:18
ENV TZ Asia/Tokyo

RUN npm install -g npm@9.6.5

COPY ./gatsby-app /app/gatsby-app
RUN npm install -g gatsby-cli
WORKDIR /app/gatsby-app

RUN yarn

