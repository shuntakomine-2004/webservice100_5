**実行したSQL文**

sqlite> CREATE TABLE users (  
(x1...>   user_id INTEGER PRIMARY KEY AUTOINCREMENT,  
(x1...>   name TEXT NOT NULL,  
(x1...>   email TEXT UNIQUE NOT NULL,  
(x1...>   age INTEGER,  
(x1...>   created_at TEXT DEFAULT CURRENT_TIMESTAMP  
(x1...> );  

sqlite> CREATE TABLE products (  
(x1...>   product_id INTEGER PRIMARY KEY AUTOINCREMENT,  
(x1...>   name TEXT NOT NULL,  
(x1...>   price INTEGER NOT NULL,  
(x1...>   stock INTEGER DEFAULT 0,  
(x1...>   created_at TEXT DEFAULT CURRENT_TIMESTAMP  
(x1...> );  



**テーブル定義確認コマンド**  

sqlite> .schema  
CREATE TABLE sqlite_sequence(name,seq);  
CREATE TABLE users (  
  user_id INTEGER PRIMARY KEY AUTOINCREMENT,  
  name TEXT NOT NULL,  
  email TEXT UNIQUE NOT NULL,  
  age INTEGER,  
  created_at TEXT DEFAULT CURRENT_TIMESTAMP  
);  
CREATE TABLE products (  
  product_id INTEGER PRIMARY KEY AUTOINCREMENT,  
  name TEXT NOT NULL,  
  price INTEGER NOT NULL,  
  stock INTEGER DEFAULT 0,  
  created_at TEXT DEFAULT CURRENT_TIMESTAMP  
);
