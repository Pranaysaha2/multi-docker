FROM node:alpine
WORKDIR "/wls"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]