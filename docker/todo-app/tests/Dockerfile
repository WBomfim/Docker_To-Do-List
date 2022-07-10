FROM mjgargani/puppeteer:trybe1.0
WORKDIR /qa_tests
COPY . /qa_tests
ADD node_modules.tar.gz /qa_tests
CMD ["npm", "test"]
