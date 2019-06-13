# Bamazon_Customer
An Amazon-like storefront with the MySQL

NPM packages installed:
* msql
* inquirer 

** How it works video:** https://youtu.be/GXHQueqBkMw

* Database is preopulated  with around 10 different products. 

* A node application called `bamazonCustomer.js`first displays all of the items available for sale.

* The app then prompts users with two messages.

   * The first one asks them the ID of the product they would like to buy.
   * The second asks how many units of the product they would like to buy.

* Once the customer has placed the order, the application checks if the store has enough of the product to meet the customer's request.

   * If not, the app logs a phrase  `Insufficient quantity!`, and then prevents the order from going through.

* If the store does have enough of the product, it fulfills the customer's order.
   * This means updating the SQL database to reflect the remaining quantity.
   * Once the update goes through, the app shows the customer the total cost of their purchase.


## Authors

* **Andrey Nelepov** - *all the work* - [andrewnelp](https://github.com/andrewnelp)

## License

This project is licensed under the ISC License