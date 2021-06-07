Make a empty folder and unzip the zip file there
Update database details in .env file
Run the following commands on project root directory
composer install
nmp install
php artisan migrate
php artisan db:seed --class=CreateAdminUserSeeder
php artisan db:seed --class=AuthorSeeder
Login with phone: 1234567891 and password : 123456
Add Book with authors and check books listing with authors
Thanks!
