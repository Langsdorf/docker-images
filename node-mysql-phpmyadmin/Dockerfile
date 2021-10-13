FROM node:lts-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN pwd
CMD ["npm", "run", "start:docker"]