FROM mysql:5.7.25
LABEL "Project"="BLB"
LABEL "Author"="BE-LIKE-BRO"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
