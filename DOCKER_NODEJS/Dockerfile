# Has Node,NPM and Yarn Installed
FROM node:14  

# sets the curent working directory so that all subsquent command will run from this in 
# Docker Virtual Image
WORKDIR /usr/src/app

# Copy package json file from here to Docker working directory
COPY package*.json ./ 
# Opens terminal and runs the code provided
RUN npm install

# Copy all from here to there
COPY . .

# Run app
CMD [ "npm", "run", "dev" ]