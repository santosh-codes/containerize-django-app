FROM node:18-alpine as BUILDER
WORKDIR /app
COPY front-end-nextjs/package.json front-end-nextjs/package-lock.json ./
COPY front-end-nextjs/ ./
RUN npm install 
COPY . ./
RUN npm run build
EXPOSE 3000
CMD [ "npm", "start" ]



