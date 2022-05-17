FROM node:14-alpine
WORKDIR /app/front-end
ADD node_modules.tar.gz /app/front-end
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
