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




pagination
--------------------------------------------------------------------------------

npm checkout pagination
npm run serve


git submodule add https://github.com/jeffreybiles/advanced-components-slots.git

https://stackoverflow.com/questions/69665222/node-js-17-0-1-gatsby-error-digital-envelope-routinesunsupported-err-os


"scripts": {
    "serve": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve",
    "build": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service build",
    "lint": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service lint"
},



Dans 'DataLoader'

  /*
  let results = await this.axios.get(this.endpoint, {
    headers: {
      'Authorization': `token ${this.authToken}`
    }
  });
  */



