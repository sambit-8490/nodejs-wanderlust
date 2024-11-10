FROM node:slim

WORKDIR /app

COPY . .
RUN npm install

COPY .env.sample .env
EXPOSE 5000

CMD ["npm", "start"]
