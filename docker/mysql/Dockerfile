FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=laravel \
  MYSQL_USER=kazuki \
  MYSQL_PASSWORD=25251061k \
  MYSQL_ROOT_PASSWORD=25251061k \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf
WORKDIR /var/www