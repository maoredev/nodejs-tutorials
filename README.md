# nodejs-tutorials
Tutoriels nodes


```

npm install
npm run dev




https://www.youtube.com/watch?v=qZXt1Aom3Cs



Options API
--------------------------------------------------------------------------------
git submodule add https://github.com/or-abdillh/echo-wallet.git
git submodule add https://github.com/or-abdillh/omdb-app.git



Compositon API
--------------------------------------------------------------------------------
git submodule add https://github.com/or-abdillh/travel-app-2.git
git submodule add https://github.com/or-abdillh/travel-app-3.git
git submodule add https://github.com/or-abdillh/marketplace-1.git
git submodule add https://github.com/or-abdillh/house-finder-app.git
git submodule add https://github.com/or-abdillh/chat-app.git
git submodule add https://github.com/or-abdillh/Todo.git
git submodule add https://github.com/or-abdillh/vegetable-app.git
git submodule add https://github.com/or-abdillh/stock-app.git

git submodule add https://github.com/or-abdillh/doctalk.git
--------------------------------------------------------------------------------












git submodule add https://github.com/or-abdillh/stock-api.git
--------------------------------------------------------------------------------



mysql -u root
CREATE DATABASE stockapi;
GRANT ALL PRIVILEGES ON *.* TO 'stockapiuser'@'localhost' IDENTIFIED BY 'StockPass';
mysql -u stockapiuser -pStockPass stockapi < ./DB/stockAppDB.sql
mysql -u stockapiuser -pStockPass


SHOW DATABASES;
USE stockapi;


npm start

conn.js
var mysql = require('mysql');

var conn = mysql.createConnection({
  host: 'localhost',
  user: 'stockapiuser',
  password: 'StockPass',
  database: 'stockapi',
  multipleStatements: true
});

conn.connect(err => {
  if (err) throw err;
  console.log('MySQL connected !!');
});

module.exports = conn;


```
