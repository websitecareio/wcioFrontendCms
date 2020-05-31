# wcioFrontendCms
## A CMS to make simple websites with user uploaded content. 

# Installation
Upload the .sql file to your databse

Edit the file: /configs/dbConnection.sample.php 
```
    $dbh = new PDO("mysql:dbname=XXXXXXXXX;port=XXXXXXXXX;host=XXXXXXXXX", "USERNAME", "PASSWORD");
```
Change XXXXXXX, USERNAME and PASSWORD to match your server information.
