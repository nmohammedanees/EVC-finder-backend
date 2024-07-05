FROM node:14
WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

# Define the command to run the app
CMD ["node", "server.js"]
