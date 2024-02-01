FROM postgres:latest
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=1234zxcv
ENV POSTGRES_DB=db_registration
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 5432