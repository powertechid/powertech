db:
  image: mysql:latest
  environment:
    MYSQL_ROOT_PASSWORD: "BiznetGio123"

wordpress:
  image: wordpress:latest
  ports:
    - "80:80"
  links:
    - db:mysql
  volumes:
    - uploads.ini:/usr/local/etc/php/conf.d/uploads.ini
