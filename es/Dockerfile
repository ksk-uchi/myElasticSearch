FROM docker.elastic.co/elasticsearch/elasticsearch:6.5.4

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/config/
COPY ./config/log4j2.properties /usr/share/elasticsearch/config/

RUN elasticsearch-plugin remove ingest-geoip
# kuromojiをインストール
RUN elasticsearch-plugin install analysis-kuromoji

