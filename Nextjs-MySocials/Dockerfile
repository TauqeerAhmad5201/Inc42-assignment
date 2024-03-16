# Next.js Dockerfile
FROM node:21-alpine3.18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

# Build your Next.js app
RUN npm run build

EXPOSE 3000

CMD ["npm", "start"]
