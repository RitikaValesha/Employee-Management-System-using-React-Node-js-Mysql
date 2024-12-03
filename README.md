# Employee-Management-System-using-React-Node-js-Mysql

Prerequisites:-
VS code,Noje js,mysql workbench

Front-End Folder
Set up:-
npm install
npm install axios bootstrap react-router-dom bootstrap-icons
npm run dev


Database
Create a database employeems
Create a table "admin" including columns:- id(Primary Key),email and password
Create a table "category" including columns:- id(Primary Key),name
Create a table "employee" including columns:- id(Primary Key),name, email, password , salary, address, image and category_id(Foreign key)

Server Side
Setup:-
npm init -y
npm install express mysql2 cors cookie-parser bcrypt jsonwebtoken multer path nodemon
npm start
