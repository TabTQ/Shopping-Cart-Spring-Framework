# Shopping-Cart-Spring-Framework
 A simple Shopping cart app based on Spring Framework

# Installation
1. CREATE DATABASE shoppingcart;
2. CHANGE these values as per your configuration in application.properties (without quotes)
   spring.datasource.username="your username"
   spring.datasource.password="your password"
   
# Usage
1. run  src\main\java\com\example\demo\SpringwebjpaApplication
2. open any browser and go to link - http://localhost:8080/
3. for first run - click on admin and add items by clicing "Add a predefined List of Items in database"
   or add items as per your specifications by clicling on "Add New Item"
   Note - When adding new item enter shopno as 1 if it is a fruit, 2 if it is a vegetable or 3 for grocery
4. Go to homepage and register a new user.
5. login now to access shopping cart and add items using "Add to Cart" button (clicking on it will increase
   the item quantity in cart by 1, repeatedly press it to increase quantity)
6. click on next shop and add items
7. then click on download invoice, it will show the total amount to pay and the items in cart.
