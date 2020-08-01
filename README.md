# Shopping Cart In PHP

A shopping cart system made with php pdo and mysqli.

## Features

Features include: <br>
* List of products<br>
* Place order<br>
* Update order<br>
* Remove order<br>
* Add to cart<br>
* Products Description<br>


## File Structure

<b>* functions.php</b> — This file contains all the functions we need for our shopping cart system (template header, template footer, and database connection functions).<br>
<b>* index.php</b> — This file contains the master template (header, footer, etc) and basic routing so we can include the pages below. <br>
<b>* home.php</b> — This file will be the home page, this will contain a featured image and 4 recently added products.<br>
<b>* products.php</b> — This file will be for displaying all products with basic pagination.<br>
<b>* product.php</b> — This file will display a product (depends on the GET request) and will contain a form that will allow the user to change the quantity and add to cart the product.<br>
<b>* cart.php</b> — The shopping cart page, this will list all the products that have been added to cart, along with the quantities, total prices, and subtotal price.<br>
<b>* placeorder.php</b> — A basic message that will be displayed to the user when they place an order on the shopping cart page.<br>
<b>* style.css</b> — The stylesheet (CSS3) we'll use for our shopping cart website.<br>
<b>* imgs</b> — This folder contains all the images for our shopping cart system, this includes featured images and product images.<br>

## How to Use
To use this project: <br>
* Open `localhost:8080/phpmyadmin` or `localhost:10000` based on your server configuration<br>
* Create a database named `shoppingcart` <br>
* In shoppingcart database, import `table.sql` file into the db <br>
* Press go to execute SQL codes.<br>
* In the browser, type `localhost:8080/shoppingcart` to see the project in action.

Do rate a star 🌟

## Issues
If there is an/any issue/bug with this project, kindly submit an issue report. 