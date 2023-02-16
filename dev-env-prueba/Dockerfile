FROM node:16

# Create app directory
WORKDIR /usr/src/dev-env-prueba

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

EXPOSE 3997
CMD [ "npm", "start" ]
