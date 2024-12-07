# Facook

## Local Development

Make sure you have PHP installed on your local machine. Just type `php -v` to check if you have PHP installed. If you have, use the built-in web server of PHP to run the project: `php -S localhost:8888` (replace `8888` with any number you wish to use for your port).

Otherwise, you could simply use XAMPP or MAMP instead.

## .htaccess

If you want to use the project with XAMPP or MAP, you should use the same configuration inside the `.htaccess.example` to ensure XAMPP or MAMP will always load the `index.php` file on all endpoint. Otherwise, you'll face a 404 Not Found and can't handle the route dynamically.