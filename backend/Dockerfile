# Dockerfile for Backend
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY . ./

# Install dependencies
RUN npm install

# Expose the backend port
EXPOSE 5555

# Start the application
CMD ["npm", "run", "dev"]
