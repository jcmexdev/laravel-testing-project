<p  align="center">
<img  src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg"  width="400">
</p>

#  Laravel Testing Project
  
## About this project

This is a basic Laravel system where i made some test using TDD methodology, it has a API to create a posts and i made tests for testing all methods in the controller for this resource.

## Installation
Install project dependencies 
```shell
composer install
``` 
Configure .env file
```
cp .env.example .env
```

Generate app key 
```
php artisan key:generate
```
Finally run tests
```
php artisan run test
```
or 
```
vendor\bin\phpunit
```

And this is the result
![Imgur](https://i.imgur.com/mfgSKzd.png)
  

## Stack
- [Laravel](https://laravel.com)
Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:
	-   [Simple, fast routing engine](https://laravel.com/docs/routing).
	-   [Powerful dependency injection container](https://laravel.com/docs/container).
	-   Multiple back-ends for  [session](https://laravel.com/docs/session)  and  [cache](https://laravel.com/docs/cache)  storage.
	-   Expressive, intuitive  [database ORM](https://laravel.com/docs/eloquent).
	-   Database agnostic  [schema migrations](https://laravel.com/docs/migrations).
	-   [Robust background job processing](https://laravel.com/docs/queues).
	-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

	Laravel is accessible, powerful, and provides tools required for large, robust applications.
- [PHP Unit](https://phpunit.de)
	PHPUnit is a programmer-oriented testing framework for PHP
  

## Contributing
Thank you for considering contributing on this project!. You can create a pull request and send your contribution.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
