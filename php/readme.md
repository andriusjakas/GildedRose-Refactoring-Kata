
## Set up development enviroment

```bash
cd php

docker run --rm -it -v $PWD:/app -w /app composer:1.8.4 require --dev phpunit/phpunit ^8

docker run --rm -it -v $PWD:/app -w /app php:7.3.2-cli-alpine3.8 vendor/bin/phpunit
```