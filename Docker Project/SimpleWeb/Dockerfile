# Specify Base Image
FROM node:alpine
 
# Work Directory
WORKDIR /usr/app

copy ./ ./
 
# Install Dependencies
RUN npm install
 
# Startup Command
CMD ["npm", "start"]