FROM node:14-alpine
WORKDIR /usr/local/
COPY ./ /usr/local/
EXPOSE 3000
ADD node_modules.tar.gz /usr/local/
ENTRYPOINT ["npm", "start"]
