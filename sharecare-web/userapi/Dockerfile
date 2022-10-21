FROM node:16-alpine 
WORKDIR /app 
ENV DATABASE_HOST="localhost" 
ENV DATABASE_PORT="54320" 
ENV DATABASE_USERNAME="postgres" 
ENV DATABASE_PASSWORD="foo" 
ENV DATABASE_NAME="sharecare" 
COPY . . 
RUN npm install 
EXPOSE 3000 
ENTRYPOINT ["node", "src/index.js"]
