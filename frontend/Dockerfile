FROM node:15

WORKDIR /app 

COPY package.json ./ 
RUN npm install --silent 


COPY . ./ 

ENTRYPOINT ["npm","start"]
