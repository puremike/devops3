FROM mysql:8.0.33

LABEL "Project"="Vprofile"

ENV MYSQL_ROOT_PASSWORD="vprodbpass"

COPY db_backup.sql docker-entrypoint-initdb.d/db_backup.sql