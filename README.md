# Docker Composer

This runs php composer in a docker container.

## Usage

It is very easy to run a composer command in the docker container.
For example composer install:

```
docker run --rm -v $(pwd):/app mc388/composer install
```
