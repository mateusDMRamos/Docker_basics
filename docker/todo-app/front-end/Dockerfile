FROM node:14
COPY ./ /usr/local/
EXPOSE 3000
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
