# Dockerfile for Backend
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy Copy frontend source code
COPY . ./

# Install dependencies
RUN npm install

# Expose the frontend port
EXPOSE 5555

# Start the application
CMD ["npm", "run", "dev"]
