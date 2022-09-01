FROM node:v16.17.0
WORKDIR /app
COPY package*.json ./
RUN mpm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]

