FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

# VOLUME [ "/app/package.json" ]

CMD [ "npm", "start"]