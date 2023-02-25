FROM node:16-alpine3.16

ENV PORT=3000

WORKDIR /frontend-react-js

COPY . .

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "start"]
