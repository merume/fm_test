FROM node:18
ENV TZ Asia/Tokyo

COPY ./piral-app /app/piral-app
RUN npm install -g npm@9.6.5 && npm install -g piral-cli 

WORKDIR /app/piral-app
RUN npm install
