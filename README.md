# simple-mysql-dump

An simple container that uses the mysql client and crond to create a database dump. 

These environment variable must be set:

CRON: cron when to run backup 
MYSQL_HOST: database host ip or name
MYSQL_USER: database user used to connect
MYSQL_PASSWORD: password
MYSQL_DATABASE: the database to backup

Add a volume that points to /usr/local/bin/backup inside the container.

See docker-compose for a sample.

