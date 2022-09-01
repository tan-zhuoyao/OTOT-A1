FROM node:12.16.3

WORKDIR /code

ENV PORT 8080

COPY package.json /code/package.json

RUN npm install --quiet

COPY . /code

CMD ["node", "index.js"]