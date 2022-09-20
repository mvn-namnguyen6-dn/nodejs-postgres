FROM node:18.9.0
WORKDIR /app
COPY ./package.json ./
RUN npm install -g npm@8.19.2
COPY . .
CMD ["npm", "run", "start"]