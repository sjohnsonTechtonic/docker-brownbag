# which image you want to start from
FROM node:alpine

# share this port with your operating system
EXPOSE 3000

# change to this directory in the container, create it if it doesn't exist
WORKDIR /app

# install system dependecies
RUN npm install -g yarn

# copy your source
COPY . .

# install source dependencies
RUN yarn

# run the app

CMD ["yarn", "start"]