FROM docker.elastic.co/elasticsearch/elasticsearch:7.9.1

RUN elasticsearch-plugin install analysis-icu
RUN elasticsearch-plugin install analysis-kuromoji
RUN elasticsearch-plugin install -b ingest-attachment