FROM node:14
COPY ./ /usr/local/backend
EXPOSE 3000
ADD node_modules.tar.gz ./
ENTRYPOINT ["npm", "start"]
