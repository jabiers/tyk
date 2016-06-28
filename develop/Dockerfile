FROM busybox:ubuntu-14.04
MAINTAINER Jacob <jacob@ntcon.co>

ADD ./stage/tyk /bin/tyk
ADD ./develop/tyk.conf /etc/tyk/tyk.conf
ADD templates/ /etc/tyk/templates/

EXPOSE 80

ENTRYPOINT ["/bin/tyk"]
CMD []