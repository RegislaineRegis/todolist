FROM node:14-alpine 
WORKDIR /app/back-end
ADD node_modules.tar.gz /app/back-end
COPY . .
EXPOSE 3001
CMD ["npm", "start"]