# E-Commerce Back End

This is the back end for an e-commerce site that utilizes Express.js while using Sequelize to interact with a MySQL database. It allows a user to create, delete, and update the following: categories, products, and tags.

## Demonstration Video

[Click here for a demonstration on how this works!](https://watch.screencastify.com/v/RsrVaT4RFQbGcRh5E9CH)

## Installation

To properly run this, you will need to do the following in the terminal:

In Bash Terminal:

```bash
npm install
mysql -u root -p
```

In MySQL Terminal:

```mysql
source db/schema
```

After the database has been created return to the Bash Terminal:

```bash
npm run seeds
nodemon server.js
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
