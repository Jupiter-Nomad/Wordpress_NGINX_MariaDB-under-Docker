RE: docker-compose.yml

You will want to adjust the following properties before composing:

MYSQL_DATABASE: "mariadb"
MYSQL_USER: "user"
MYSQL_PASSWORD: "password"
MYSQL_ROOT_PASSWORD: "rootpassword"

WORDPRESS_DB_HOST: "db"
WORDPRESS_DB_NAME: "mariadb"
WORDPRESS_DB_USER: "user"
WORDPRESS_DB_PASSWORD: "password"


RE: nginx.conf
You will want to adjust the following properties before composing:

server_name 
