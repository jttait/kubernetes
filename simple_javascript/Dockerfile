FROM node:alpine

COPY package.json package.json
RUN npm install

EXPOSE 8000

COPY . .

CMD ["npm", "start"]
