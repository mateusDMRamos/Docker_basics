FROM mjgargani/puppeteer:trybe1.0
COPY ./ /usr/local/
EXPOSE 3000
ADD node_modules.tar.gz ./usr/local/
ENTRYPOINT ["npm", "test"]