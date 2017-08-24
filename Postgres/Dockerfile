FROM postgres:9.6.3-alpine
MAINTAINER Juan Carlos Santos “juancarlosgrc38Qgmail.com”
COPY posts_v2.sql /docker-entrypoint-initdb.d/
ENV PGDATA/var/libpostgresql/data
VOLUME/var/libpostgresql/data
ENTRYPOINT [“/docker-entrypoint.sh”]
EXPOSE 5432
CMD [“postgres”]
