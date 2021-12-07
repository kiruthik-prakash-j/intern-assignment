# Using official MySQL as a base image
FROM mysql:8.0.26

LABEL Author="Kiruthik Prakash J"

COPY ./scripts/ /docker-entrypoint-initdb.d/

EXPOSE 3306