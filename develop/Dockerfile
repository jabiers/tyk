FROM busybox:ubuntu-14.04
MAINTAINER Jacob <jacob@ntcon.co>

ADD stage/tyk /bin/tyk
ADD develop/tyk.conf /opt/tyk-gateway/tyk.conf
ADD / /opt/tyk-gateway/

EXPOSE 80

ENTRYPOINT ["/bin/tyk", "--conf=/opt/tyk-gateway/tyk.conf"]
CMD []