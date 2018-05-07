# dbdynamicecom
This repo contains the store module for DoubleBattery (The Optical Studio).
# Build Instructions
Step 1: Clone the repository: "git clone https://github.com/deardev/dbdynamicecom.git"

Step 2: Copy the WordPress "theme" folder from your own repository to dbdynamicecom -> public folder

Step 3: Go back to the dbdynamicecom folder

Step 4: Run "composer install"

Step 5: include a .env file as per your requirement

Step 6: make sure your env file contains...

        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=doubleBattery
        DB_USERNAME=root
        DB_PASSWORD=

Step 7: create a database in mysql named "doubleBattery"

Step 8: import 'doubleBattery.sql' from database folder of this repository to the local database you just created

Step 9: Run "php artisan serve"

Step 10: Click on "EYEWEAR" or "SUNGLASSES" menu items or the 'SHOES' banner at the home page

Step 11: Click on floral print image

Step 12: Update quantity and click on 'Add to Cart'

Step 13: You will see the updated cart icon at the top-right header of the page. Hovor there to see details.

Step 14: At present you can open 3 more pages along with the home page (which was already there as a static page). Those are a) the product shop page, b) product item detail page and c) the cart page.

Step 15: The operation is dynamic through the MySQL database, but currently you can add a product to the cart only from the product detail page and only the floral print product will work.
