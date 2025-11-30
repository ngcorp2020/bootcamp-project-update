FROM mysql:8

ENV MYSQL_ROOT_PASSWORD=rootpass
ENV MYSQL_DATABASE=mydb

# Script lancé automatiquement à l'initialisation
COPY create.sql /docker-entrypoint-initdb.d/
