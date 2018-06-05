#dbv

*	modify volume/config.php

*	Dockerfile

	1.	`docker build . dbv:latest`
	2.	`docker run -p 8080:80 -d --name dbv -v "$PWD/volume/config.php":/var/www/html/dbv/config.php -v "$PWD/volume/data":/var/www/html/dbv/data/ dbv`

*	Docker CLI

	1.	`docker run -p 8080:80 -d --name dbv -v "$PWD/volume/config.php":/var/www/html/dbv/config.php -v "$PWD/volume/data":/var/www/html/dbv/data/ registry.cn-hangzhou.aliyuncs.com/yudada/dbv:latest`