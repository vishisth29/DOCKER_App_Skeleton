FROM postgres:9.6

MAINTAINER Vishsith "vishisth@claimfound.com"
# By copying it to below directory, init.sql runs each time the postgres container is started.
COPY init.sql /docker-entrypoint-initdb.d