FROM node:14
COPY ./ /usr/local/
EXPOSE 3001
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]