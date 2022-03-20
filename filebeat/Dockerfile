FROM docker.elastic.co/beats/filebeat:8.0.1
COPY filebeat.docker.yml /usr/share/filebeat/filebeat.yml
USER root
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
RUN chmod go-w /usr/share/filebeat/filebeat.yml
