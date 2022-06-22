FROM node:12

EXPOSE 5000

WORKDIR /var/src/app

COPY backend-api/package*.json ./

RUN npm install

COPY . .