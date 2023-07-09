ARG ELASTIC_VERSION

FROM elastic/filebeat:${ELASTIC_VERSION}
USER root
RUN mkdir -p ./log
WORKDIR /logs
COPY core.log ./log/