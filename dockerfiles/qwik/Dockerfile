FROM node:18
ENV TZ Asia/Tokyo

RUN apt update && apt install -y xdg-utils --fix-missing
COPY ./qwik-app /app/qwik-app
RUN npm install -g npm@9.6.5 
WORKDIR /app/qwik-app
RUN npm install

