FROM node:carbon

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

# EXPOSE 81/tcp

# EXPOSE 8080/udp


CMD ["npm", "start"]
