FROM alpine:3.9
COPY backup /usr/local/bin/backup
RUN chmod 700 /usr/local/bin/backup
COPY startup /usr/local/bin/startup
RUN chmod 700 /usr/local/bin/startup
RUN apk add --no-cache mysql-client
CMD /usr/local/bin/startup
