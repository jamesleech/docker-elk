FROM elasticsearch:latest
MAINTAINER james.leech@tattsgroup.com

#RUN apt-get update
#COPY entrypoint.sh /tmp/entrypoint.sh
#RUN chmod +x /tmp/entrypoint.sh

RUN /usr/share/elasticsearch/bin/plugin install royrusso/elasticsearch-HQ

EXPOSE 9200 9300
