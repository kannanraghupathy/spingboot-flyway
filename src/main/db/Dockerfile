FROM postgres:9.5.1
MAINTAINER kannanraghupathy@gmail.com
ENV POSTGRES_USER docker
ENV POSTGRES_DB mydb
COPY 1_schema.sql /docker-entrypoint-initdb.d/
COPY 2_data.sql /docker-entrypoint-initdb.d/
