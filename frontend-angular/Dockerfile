FROM node:12

EXPOSE 4200

WORKDIR /var/usr/src

COPY package*.json ./

RUN npm install

COPY . .

CMD ["npm", "run" , "start"]