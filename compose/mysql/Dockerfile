FROM mysql:5.7
RUN chown -R mysql:root /var/lib/mysql/

ARG MYSQL_DATABASE
ARG MYSQL_USER
ARG MYSQL_PASSWORD
ARG MYSQL_ROOT_PASSWORD

ENV MYSQL_DATABASE="sails_docker"
ENV MYSQL_USER="sails"
ENV MYSQL_PASSWORD="sails"
ENV MYSQL_ROOT_PASSWORD="sails"

#ADD data.sql /etc/mysql/data.sql
#RUN sed -i 's/MYSQL_DATABASE/'$MYSQL_DATABASE'/g' /etc/mysql/data.sql
#RUN cp /etc/mysql/data.sql /docker-entrypoint-initdb.d

EXPOSE 3306