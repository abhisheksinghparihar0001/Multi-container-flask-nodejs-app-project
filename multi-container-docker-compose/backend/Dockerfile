# Use the official Node.js image as base
FROM node:16

# Set working directory in the container
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json /app/
RUN npm install

# Copy all the files into the container
COPY . /app/

# Expose the port the app runs on
EXPOSE 3000

# Command to run the app
CMD ["npm", "start"]
