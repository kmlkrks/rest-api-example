Example Rest Api project
--------------
Example rest api project with symfony 3

####Requirements

* php >= 5.4
* mysql-client
* redis

####Installation
Clone repository from git

	https://github.com/kmlkrks/restapi-example.git

Install composer

	curl -sS https://getcomposer.org/installer | php
	sudo mv composer.phar /usr/local/bin/composer

Install dependencies

	composer install

Running built-in web server

	php bin/console server:run
