FROM node:22-alpine AS prod

WORKDIR /app

COPY package*.json ./

RUN npm install --omit=dev

COPY . .

RUN npm install

EXPOSE 5000

CMD ["node", "src/server.js"]

FROM node:22-alpine AS dev

WORKDIR /src

ENV PORT=5000
ENV MONGODB_URI=mongodb://mongo:27017/pennywise_db?authSource=admin

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "run", "dev" ]