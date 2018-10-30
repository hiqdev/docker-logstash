FROM docker.elastic.co/logstash/logstash-oss:6.4.2

RUN logstash-plugin install logstash-input-jdbc && \
	mkdir -p /usr/share/logstash/vendor/jar/jdbc && \
	cd /usr/share/logstash/vendor/jar/jdbc && \
	curl -O https://jdbc.postgresql.org/download/postgresql-42.2.5.jar

