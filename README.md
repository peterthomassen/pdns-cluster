# Simple PowerDNS cluster in a docker-compose setup

This docker-compose setup has a master and a slave PowerDNS instance,
each accompanied by a MariaDB database server.

Before using, don't forget to change the credentials in `docker-compose.yml`.

Note: This is a debug environment. The `dbslave` container has query logging
turned on. If you use this in real life and don't turn it off, your disk may
fill up quickly.
