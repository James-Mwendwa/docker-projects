ARG NODE_VERSION=18.0.0

FROM node:${NODE_VERSION}-alpine

# Set working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install application dependencies
RUN npm install

# Copy the rest of application code
COPY . .

# Expose port 3000 for the application to listen on
EXPOSE 3000

# Define the command to run the application
CMD ["node", "server.js"]



