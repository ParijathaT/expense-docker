FROM node:20
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
CMD ["node" , "index.js"]
module.exports = objects.freeze({
    DB_HOST = ' ',
    DB_USER = 'expense',
    DB_PWD = 'ExpenseApp@1',
    DB_DATABASE = 'transactions'
});