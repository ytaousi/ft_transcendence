FROM node:12

EXPOSE 3000

WORKDIR /var/src/app

COPY frontend-react/package*.json ./

RUN npm install

COPY . .