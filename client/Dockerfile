# Use the official Node.js image
FROM node:latest

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install

# Copy the application code
COPY . .

# Expose port and run
EXPOSE 3000

CMD ["npm", "start"]
