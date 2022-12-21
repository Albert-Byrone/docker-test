FROM node:14-alpine
# Add a work directory
WORKDIR /app

COPY ./package.json /app
COPY ./package*.json /app
# COPY package.json ./
# COPY ./package.json ./

# RUN npm cache clean --force
COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm","run","start"]
