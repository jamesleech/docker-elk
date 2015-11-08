FROM elasticsearch:2
MAINTAINER james.leech@tattsgroup.com

#RUN apt-get update
#COPY entrypoint.sh /tmp/entrypoint.sh
#RUN chmod +x /tmp/entrypoint.sh

RUN /usr/share/elasticsearch/bin/plugin install royrusso/elasticsearch-HQ
#RUN /usr/share/elasticsearch/bin/plugin install lukas-vlcek/bigdesk/v2.5.0
RUN /usr/share/elasticsearch/bin/plugin install lmenezes/elasticsearch-kopf
#RUN /usr/share/elasticsearch/bin/plugin install karmi/elasticsearch-paramedic
#RUN /usr/share/elasticsearch/bin/plugin install mobz/elasticsearch-head

EXPOSE 9200 9300
