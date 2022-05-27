FROM mysql:8.0

ENV MYSQL_DATABASE=sg_db \
  MYSQL_USER=waraeba \
  MYSQL_PASSWORD=waraeba \
  MYSQL_ROOT_PASSWORD=waraeba \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 644 /etc/mysql/conf.d/my.cnf