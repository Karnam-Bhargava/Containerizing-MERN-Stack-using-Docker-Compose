# Base Image
FROM node:18

# Working directory 
WORKDIR /app

# Copying package.json from local to working directory
COPY package.json .

# Installing npm on Container
RUN npm install

# Copying the source code to working directory
COPY . .

# Expose Port
EXPOSE 5173

# Default commands that runs when docker container starts
CMD [ "npm", "run", "dev" ]
