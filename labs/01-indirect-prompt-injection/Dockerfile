FROM node:22-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY vulnerable-agent.js attack.js ./

CMD ["npm", "start"]
