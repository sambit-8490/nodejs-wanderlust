FROM node:slim

WORKDIR /app

COPY . .
RUN npm install

COPY .env.sample .env
EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host"]
