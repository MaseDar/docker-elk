ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM logstash:${ELASTIC_VERSION}
USER root
RUN mkdir -p /log
WORKDIR /logs
COPY core.log /log/

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
