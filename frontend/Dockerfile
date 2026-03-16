FROM node:18

WORKDIR /app

ENV NODE_ENV=development

COPY package.json .

RUN npm install

COPY . .

CMD ["npm", "start"]