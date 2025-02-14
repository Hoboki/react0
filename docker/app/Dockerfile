FROM node:17-alpine

WORKDIR /var/www/react0/app

COPY react0/app/package.json .

RUN npm install

EXPOSE 3000
CMD ["npm", "start"]
