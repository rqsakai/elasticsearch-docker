FROM docker.elastic.co/elasticsearch/elasticsearch:6.8.11
MAINTAINER Raul Sakai rqsakai@gmail.com

RUN elasticsearch-plugin install --batch analysis-phonetic
RUN elasticsearch-plugin install --batch analysis-icu
