
## Set up development enviroment

```bash
cd php

docker run --rm -it -v $PWD:/app -w /app composer:1.8.4 require --dev phpunit/phpunit ^8


```