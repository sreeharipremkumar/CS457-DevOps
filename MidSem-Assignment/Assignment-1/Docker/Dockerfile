FROM node:14

WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm Install

# Bundle app source
COPY . .

CMD ["npm", "start"]