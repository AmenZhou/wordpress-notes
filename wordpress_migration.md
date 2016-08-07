### Ubuntu

#####  Install PHP + Apache

1. Install `apache2`, `php5`, `php5-mysql`

2. The default apache html directory is -- /var/www/html

3. The default configuration file of apache is located in -- /etc/apache2/site-enable/

##### Import DB and Copy Folders

1. Copy the whole site folder into the new server

2. Copy `wp-config.php` to the new server, but it should one directory up to the main folder
 
   * change the db user and password

3. Create a new database, the name should match the definition in wp-config.php

4. Import the data to new database

5. Change the /etc/hosts file, add one line in the bottom -- `localhost  http://site-url`

6. Restart the apache2 service
