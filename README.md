# phpDocker
php docker file
php: 5.6

  ## 依赖镜像
  - php:5.6-cli

  ## 使用
1. build
> docker build -t your/image/name /docker/file/path
2. run
> docker run -d -p 8100:8100 --name your_container_name -v /your/code/path:/www your/image/name
3. enter docker
> docker run -it --name your_container_name your/image/name
  ## 包含扩展


- ctype
- curl
- date
- dom
- ereg
- fileinfo
- filter
- ftp
- hash
- iconv
- json
- libxml
- mbstring
- mcrypt
- mhash
- mysqlnd
- openssl
- pcre
- PDO
- pdo_mysql
- pdo_sqlite
- Phar
- posix
- readline
- redis
- Reflection
- session
- SimpleXML
- SPL
- sqlite3
- standard
- tokenizer
- xml
- xmlreader
- xmlwriter
- zlib

## todo list
- add gd ext
- add imagemagic ext
