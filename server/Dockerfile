# specify a node base image
FROM node:16

# set working directory
WORKDIR /server

# copy package.json to the working directory
COPY package.json /server

# install dependencies
RUN npm install

# Copy the entire application code to the working directory
COPY . /server

# specify the command to run when the container starts
CMD ["npm", "run", "start"]