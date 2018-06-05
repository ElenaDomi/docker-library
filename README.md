# docker-library
docker-library

docker run -p 8080:80 -d --name dbv -v "$PWD/config.php":/var/www/html/dbv/config.php -v "$PWD/data":/var/www/html/dbv/data/ dbv
