# Dockerfile for server
FROM node:latest

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json ./
RUN npm install --legacy-peer-deps

# Copy application code
COPY . .

# Expose port and run
EXPOSE 3001 

CMD ["npm", "start"]
