# Concours project NodeJS Express Sequelize

### 1. Download project's folder
``` git clone https://github.com/Luc010/concoursNodeJSExpress.git ```

### 2. Open project's folder and your terminal

### 3. Depedencies:
``` npm install ``` 

### 4. Manager models install: 
``` cd node_modules/.bin/ ```
``` sequelize init ```

### 5. Model's creation:
``` sequelize model:generate --name User --attributes firstname:string,lastname:string,age:integer,level:string,address:string,city:string,country:string,zip:string,social_num:integer,social_network:string,username:string,email:string,password:string ```

### 6. Database's creation:
``` sequelize db:create ```

### 7. Table's creation:
``` sequelize db:migrate ```



### References:
``` https://steemit.com/nodejs/@siddub/user-login-and-registration-in-nodejs-using-express-bycrpt-and-mysql ```