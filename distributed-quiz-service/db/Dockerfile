FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD=1234
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306