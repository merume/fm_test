FROM node:18
ENV TZ Asia/Tokyo

COPY ./nuxt3-app /app/nuxt3-app
RUN npm install -g npm@9.6.5 
WORKDIR /app/nuxt3-app
RUN yarn install

