FROM postgres:9.6
RUN apt-get update && apt-get install -y postgresql-9.6-plv8
RUN echo 'CREATE EXTENSION plv8;' > /docker-entrypoint-initdb.d/plv8.sql
RUN apt-get clean \
  && apt-get autoremove -y \
  && rm -rf /tmp/build /var/lib/apt/lists/*