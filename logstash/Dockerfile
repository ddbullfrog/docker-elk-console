FROM docker.elastic.co/logstash/logstash:5.6.2

COPY ./config/logstash.yml /usr/share/logstash/config/
COPY ./pipeline/logstash.conf /usr/share/logstash/pipeline/

CMD logstash -f /usr/share/logstash/pipeline/logstash.conf