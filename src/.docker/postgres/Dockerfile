FROM ubuntu/postgres:latest

RUN mkdir -p /docker-entrypoint-initdb.d

COPY setup.sql /docker-entrypoint-initdb.d

EXPOSE 5432

