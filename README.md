## ToDoList
A Vue.js, Express.js , MySql web appilcation for keeping  activities. This project is seperated as client and server.

### Setup Project with sketch
# Client
        - Use vue template: npm install -g vue-cli
        - Create client project: vue init webpack client
        - Install npm: cd client, npm install
        - Install axios to get HTTP request: npm install --save axios
        - npm install vue bootstrap-vue bootstrap
# Server:
        - Make new folder: mkdir server
        - Create package.json file: npm init -f
        - EsLint: npm install --save nodemon eslint
        - Install Express and body-parser: npm install --save express body-parser cors morgan
        - Use Sequelize for database: npm install --save sequelize
        - npm install --save mysql2

### Run XAMPP( Apache and MySQL)
        - Create nodejs_tasks database and table tbl_tasks(id,task_name)
### Setup: Clone the repo
# Client- Terminal A
        - cd client
        - npm install
        - npm start
# Server - Terminal B
        -cd server
        - npm install
        - npm start