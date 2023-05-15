# npx create-react-app telemy --template typescript

FROM node:18.12.1-alpine

WORKDIR /app
 
COPY package.json ./
  
RUN npm install
 
COPY . .
 
CMD ["npm", "start"]
