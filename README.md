## Php Apache Docker Image for CodeIgniter4 Framework
[![Docker Build Status](https://img.shields.io/docker/cloud/build/lucarodrigotrejo/codeigniter4-php-apache?style=for-the-badge)](https://hub.docker.com/r/lucarodrigotrejo/codeigniter4-php-apache/)
[![Docker Image Version (tag latest semver)](https://img.shields.io/docker/v/lucarodrigotrejo/codeigniter4-php-apache/1.0?style=for-the-badge)](https://hub.docker.com/r/lucarodrigotrejo/codeigniter4-php-apache/)
![Docker Pulls](https://img.shields.io/docker/pulls/lucarodrigotrejo/codeigniter4-php-apache?style=for-the-badge)

This repository provides you an environment in order to run codeigniter 4 on php-apache server.

## Usage

docker-compose.yml
```
version: "3"

services:
    codeigniter4-php-apache:
        image: lucarodrigotrejo/codeigniter4-php-apache:1.0
        container_name: 'codeigniter4-php-apache'
        ports:
          - 80:80
        volumes:
          - ./:/var/www/html
```

## Installation

Install [docker](https://docs.docker.com/engine/installation/) and [docker-compose](https://docs.docker.com/compose/install/) ;

## Contributing

Contributions are welcome!
Leave an issue on Github, or create a Pull Request.


## Licence

This work is under [MIT](LICENSE) licence.
