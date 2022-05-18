FROM node:14-alpine
WORKDIR /app/front-end
COPY . .
ADD node_modules.tar.gz /app/front-end
EXPOSE 3000
CMD ["npm", "start"]