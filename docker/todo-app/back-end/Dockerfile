FROM node:14

WORKDIR /usr/app

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 3001

CMD ["npm", "start"]

LABEL maintener="Jessy Cristina Lopes de Araujo <jessyaraujo395@gmail.com>"
