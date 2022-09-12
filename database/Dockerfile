FROM mysql:latest 
ENV MYSQL_ROOT_PASSWORD root
ADD ./database /docker-entrypoint-initdb.d
EXPOSE 3306