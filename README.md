# Laravel api resources

Laravel CRUD api using Resources

## Getting started

```bash
$ git clone https://github.com/DtecIndustries/laravel-api-resources.git
$ cd laravel-api-resources
$ cp .env.example .env
$ php artisan key:generate
$ composer install
$ docker-compose up -d
$ docker-compose exec -w /var/www app php artisan migrate:fresh --seed
```

## api endpoints

* Show posts : `GET /api/posts/`
* Show post (with id) : `GET /api/post/{id}`
* Post post : `POST /api/post/`
* Update post : `PUT /api/post/`
* Delete post : `PUT /api/post/{id}`

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).