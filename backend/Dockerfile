# Dockerfile for Backend
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy Copy backend source code
COPY . ./

# Install dependencies
RUN npm install

# Expose the backend port
EXPOSE 5555

# Start the application
CMD ["npm", "run", "dev"]
