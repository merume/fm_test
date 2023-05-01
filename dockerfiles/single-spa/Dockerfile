FROM node:18
ENV TZ Asia/Tokyo

RUN npm install --global create-single-spa
COPY ./single-spa-app /app/single-spa-app
RUN yarn
WORKDIR /app/single-spa-app

