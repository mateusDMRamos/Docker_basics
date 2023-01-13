FROM node:14
COPY ./ /usr/local/
EXPOSE 3001
ADD node_modules.tar.gz ./usr/local/
ENTRYPOINT ["npm", "start"]