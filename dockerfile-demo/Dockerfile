# Use Node.js version 20 as the base image
FROM node:20

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the package.json and package-lock.json files along with the app.js file to the working directory
COPY package*.json app.js ./

# Install dependencies
RUN npm install

# Expose the correct port number, assuming it's meant to be 3000
EXPOSE 3000

# Command to run the application
CMD ["node", "app.js"]
