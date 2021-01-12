FROM node:12
WORKDIR /usr/src/app
COPY package*.json ./
COPY .dotenv ./
RUN npm install
# RUN npm ci --only=production
COPY . .
EXPOSE 8000
CMD [ "node", "server.js" ]
