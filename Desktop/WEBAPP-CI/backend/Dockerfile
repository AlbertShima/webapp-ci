FROM node:22

WORKDIR /backend-app
COPY package.json ./
RUN npm install
COPY index.js ./
COPY .env ./

EXPOSE 5050

CMD ["npm", "start"]