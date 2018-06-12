#dbv

*	modify volume/config.php

*	Dockerfile

	1.	`docker build . dbv:latest`
	2.	`docker run -p 8080:80 -d --name dbv -v "$PWD/volume/config.php":/var/www/html/config.php -v "$PWD/volume/data":/var/www/html/data/ dbv`

*	Docker CLI

	1.	`docker run -p 8080:80 -d --name dbv -v "$PWD/volume/config.php":/var/www/html/config.php -v "$PWD/volume/data":/var/www/html/data/registry.cn-hangzhou.aliyuncs.com/yudada/dbv:latest`