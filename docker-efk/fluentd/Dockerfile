FROM fluent/fluentd:v1.12.0-1.0
USER root
RUN gem install elasticsearch -v 7.17.1
RUN gem install fluent-plugin-elasticsearch --no-document -v 5.2.4
USER fluent