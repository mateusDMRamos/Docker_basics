FROM mjgargani/puppeteer:trybe1.0
WORKDIR /usr/local/
COPY ./ /usr/local/
ADD node_modules.tar.gz /usr/local/
ENTRYPOINT ["npm", "test"]