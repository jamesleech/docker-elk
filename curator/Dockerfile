# Docker Definition for ElasticSearch Curator

FROM python:2.7.8
MAINTAINER James Leech <james.leech@tattsgroup.com>

RUN pip install --quiet elasticsearch-curator

ENTRYPOINT [ "/usr/local/bin/curator" ]
