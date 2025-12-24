# Use an official Node.js image as a base
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app
COPY . .

# Expose port and define startup command
EXPOSE 3000
CMD ["node", "index.js"]
