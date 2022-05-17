FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app/tests
ADD node_modules.tar.gz /app/tests
COPY . .
RUN npm install
CMD ["npm", "start"]

