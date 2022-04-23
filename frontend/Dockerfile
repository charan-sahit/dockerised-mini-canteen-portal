FROM node:17.0.0

WORKDIR /frontend

COPY package.json package.json
COPY package-lock.json package-lock.json 

RUN npm install
COPY . .





EXPOSE 3000

CMD ["npm" , "start"]
