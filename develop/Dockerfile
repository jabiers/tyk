FROM busybox:ubuntu-14.04
MAINTAINER Jacob <jacob@ntcon.co>

ADD ./stage/tyk /bin/tyk
ADD ./develop/tyk.conf /opt/tyk/tyk.conf
ADD templates /opt/tyk/templates

EXPOSE 80

ENTRYPOINT ["/bin/tyk"]
CMD []