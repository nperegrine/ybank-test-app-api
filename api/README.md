# yBank API
> Laravel Backend API for yBank

## Installation
1.) Install all composer dependencies
```bash
composer install
```
2.) Make sure you have the Laravel .env file in your project root and generate your APP_KEY
```bash
php artisan key:generate
```
3.) Run your database migrations and seed the database
```bash
php artisan migrate
php artisan db:seed
```
4.) You are now ready to launch your API
```bash
php artisan serve
```
## Testing
Feature tests are located in the "/tests/Feature" directory and Unit tests are located in the "/tests/Unit" directory. 
Enter the following command to run PHPUnit tests.
```bash
vendor/bin/phpnunit
```

## Remarks
The API works, I did my best within the given period of time and within the context of the test assignment to fix and finish the most common edge cases. I know there's more work than can be done to make this even better and I'm open to learning and doing more.
