FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app/tests
COPY . .
ADD node_modules.tar.gz /app/tests
CMD ["npm", "test"]