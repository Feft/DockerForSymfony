# DockerForSymfony
All needed applications to run Symfony project. Included: php-fpm, nginx, postgres.

## Installation
In your Symfony application folder run command:
```sh
git clone https://github.com/Feft/DockerForSymfony.git docker
```
Change directiory to docker/.
To run your application type:
```sh
docker-compose up -d
```
Now, go to browser, type http://localhost:8080/ and enjoy. Your application works independently of the installed software.

Based on article: https://blog.rafalmuszynski.pl/how-to-configure-docker-for-symfony-4-applications/

