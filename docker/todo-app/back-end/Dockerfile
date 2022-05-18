FROM node:14-alpine 
WORKDIR /app/back-end
COPY . .
ADD node_modules.tar.gz /app/back-end
EXPOSE 3001
CMD ["npm", "start"]