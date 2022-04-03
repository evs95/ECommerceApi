# E-Commerce Back End

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes.

This application ECommerceAPi, is back end for an e-commerce site which uses Express.js API to use Sequelize to interact with a MySQL database. Any manager at an internet retail company can use this back end for e-commerce website that uses the latest technologies so that company can compete with other e-commerce companies.

Features of the application includes
* Provides a functional Express.js API application
* Adding database name, MySQL username, and MySQL password to an environment variable file will be able to connect to a database using Sequelize
* On entering schema and seed commands, a development database is created and is seeded with test data
* On entering the command to invoke the application, server is started and the Sequelize models are synced to the MySQL database
* On opening API GET routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON
* On testing API POST, PUT, and DELETE routes in Insomnia, user will be able to successfully create, update, and delete data in database

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](/Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](/Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](/Assets/13-orm-homework-demo-03.gif)

## Application Demo Url

Below is link for demo of the application.

[E-Commerce Api Demo](https://drive.google.com/file/d/1D0y1z3O0wjL_NNmO-V5H9df_u3KzzrpI/view)