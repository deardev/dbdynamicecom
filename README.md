# doublebattery

This repo contains the store module for DoubleBattery (The Optical Studio).
# dbdynamicecom
step 1: Clone the repository: "git clone https://github.com/deardev/dbdynamicecom.git"

step 2: Go to the dbdynamicecom directory

step 3: Run "composer install"

step 4: include a .env file as per your requirement

step 3: make sure your env file contains...

        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=doubleBattery
        DB_USERNAME=root
        DB_PASSWORD=

step 4: create a database in mysql named "doubleBattery"

step 5: import 'doubleBattery.sql' from database folder of this repository to the local database you just created

step 6: Run "php artisan serve"

step 7: Click on "Sunglasses" home menu item or the 'shoes' banner at the home page

step 8: Click on floral print image

step 9: Update quantity and click on 'Add to Cart'

step 10: You will the cart icon updeted at the top-right header of the page. Hovor there to see details.

The operation is dynamic through the MySQL database, but currently you can add a product to the cart only from the product detail page and only the floral print product will work.
