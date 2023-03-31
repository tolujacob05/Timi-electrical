FROM node:19-alpine

WORKDIR /electrical

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]