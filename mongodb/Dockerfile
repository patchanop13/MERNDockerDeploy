FROM mongo:4.4.9

ENV MONGO_INITDB_ROOT_USERNAME admin
ENV MONGO_INITDB_ROOT_PASSWORD 1234
ENV MONGO_INITDB_DATABASE products

ADD ./data/products.js /docker-entrypoint-initdb.d