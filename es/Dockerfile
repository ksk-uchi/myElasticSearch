FROM docker.elastic.co/elasticsearch/elasticsearch:5.6.1

RUN elasticsearch-plugin remove ingest-geoip
# kuromojiをインストール
RUN elasticsearch-plugin install analysis-kuromoji

