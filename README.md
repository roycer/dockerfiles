# dockerfiles
Docker images for microservices

### Installation

```sh
docker build -t <name_repository:tag> -f <name new dockerfile> .
```

example:
```sh
docker build -t maypi:1.0 -f Dockerfile-nginx-php7-mysql .
```