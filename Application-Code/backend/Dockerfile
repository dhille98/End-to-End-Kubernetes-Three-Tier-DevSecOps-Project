FROM node:14
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
EXPOSE 3500
COPY . .
CMD ["node", "index.js"]