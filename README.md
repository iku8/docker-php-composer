
## Usage


```
docker compose run composer composer {command}
```

show composer version
```
docker compose run composer composer --version
```

composer install
```
docker compose run composer composer install
```

install laravel 8.0

```
docker compose run composer composer create-project --prefer-dist laravel/laravel=8.0 myApp
```

## How to composer install on other directory

```
cp .env.example .env
```

You can change composer.json path. `PATH_TO_COMPOSER_JSON`
