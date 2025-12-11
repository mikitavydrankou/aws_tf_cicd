FROM node:25
WORKDIR /usr/app
copy package.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "app.js"]