# 笔记

### 怎么打开mongodb

- 在毕设的目录下敲命令行：mongod --dbpath=./data/db
- 在bolgs-back的目录下敲命令行：mongo,然后对数据库进行编辑

### 怎么打开mongo-express

- 在blogs-back目录下敲命令行：npm list -g mongo-express，列出路径
- cd /home/liuxicui/.nvm/versions/node/v7.1.0/lib
- cd node_modules
- cd mongo-express
- cp config.default.js config.js
- vim config.js修改配置文件，数据库名，用户名密码，退出是shift+z+z
- mongo-express
