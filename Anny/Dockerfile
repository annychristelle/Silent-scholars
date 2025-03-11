# Use Node.js as base image
FROM node:18-alpine  

# Set working directory
WORKDIR /app  

# Copy package.json and install dependencies
COPY package.json .  
RUN npm install  

# Copy the rest of the code
COPY . .  

# Expose the port the app runs on
EXPOSE 3000  

# Command to start the app
CMD ["npm", "start"]
