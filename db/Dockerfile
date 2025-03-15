FROM mysql
ENV MYSQL_ROOT_PASSWORD=Pass123
ENV MYSQL_DATABASE=facebook
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
CMD ["mysqld"]
