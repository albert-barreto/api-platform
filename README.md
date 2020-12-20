# Installation

1. Install the dependencies: `composer install`
2. run migrations: `php bin/console d:m:m`
3. run fixtures: `php bin/console d:f:l --no-interaction`
4. Start the server: `symfony serve` or` php -S localhost: 3000 -t public`