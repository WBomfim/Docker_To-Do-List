FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo_tests
COPY . /todo_tests
ADD node_modules.tar.gz /todo_tests
CMD ["npm", "test"]
