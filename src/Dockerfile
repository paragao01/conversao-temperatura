FROM node:22.6.0
WORKDIR /app
COPY package*.jdon ./
RUN npm install
COPY . .
EXPOSE 8080

CMD ["node", "server.js"]
