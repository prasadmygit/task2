FROM node:current-alpine
WORKDIR /FrontEnd
COPY package*.json ./
RUN npm install
RUN yarn add react-scripts
COPY . .
EXPOSE 3000
CMD ["npm","start"]
