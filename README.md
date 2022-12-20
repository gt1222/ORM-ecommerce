# ORM-ecommerce

## Description
The hardest part about this project was making sure all my routes were working in insomnia and the routes were correct. I was stumped for a long time with the models because I kept getting an error with the `belongsToMany` being wrong and it turns out it was supposed to be `hasMany`. 

There were two errors that never changed for create and update product. However, even if it was a bad request, the data was still added and insomnia was working.

Overall, I enjoyed this project because I like working with insomnia and it went very smoothly even if there was some bumps.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Installation
1. clone repository
2. npm install mysql and sequelize
3. dotenv to use environment variable to store sensitive data

## Usage
User needs to first run mysql `mysql -u root -p` and then enter their password. Then they `source db/schema.sql`, exit mysql and `npm run seed`.

Initialize the program with `npm start`

![Demo of the assignment through mysql and in insomnia](Instructions/Assets/ORM.gif)

## Links
[Demo Link](https://drive.google.com/file/d/1eaYxQ4D904GleTcx74KBzbr59LO2_iLa/view?usp=share_link)

[Github](https://github.com/gt1222/ORM-ecommerce)