FROM node:16.14.0
WORKDIR /app
COPY ./package*.json ./
RUN npm install
COPY . .
#TESTE
EXPOSE 8080
CMD ["node", "server.js"]
