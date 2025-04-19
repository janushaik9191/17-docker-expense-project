FROM node:20
EXPOSE 8080
ENV DB_HOST="mysql"
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY TransactionService.js .
COPY DbConfig.js .
COPY index.js .
RUN npm install
CMD ["node","index.js"]