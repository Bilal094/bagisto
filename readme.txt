Documentation for setting up a bagisto project

1. Enable extension=sodium, extension=intl and extension=gd in the php.ini file
2. Run composer create-project bagisto/bagisto in the project folder
3. Open the project folder, giving the database credentials in the .env file and run php artisan bagisto:install
4. After installing/migrating the bagisto database tables
5. To have access to the website, run php artisan serve
6. Go to http://127.0.0.1:8000/

