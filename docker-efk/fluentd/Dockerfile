# FROM fluent/fluentd
# RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "5.0.5"]

# FROM fluent/fluentd:v1.15-debian-1
# USER root
# RUN gem install fluent-plugin-elasticsearch --no-document --version 5.0.5
# USER fluent

# FROM fluent/fluentd:v1.12.0-debian-1.0
# USER root
# RUN gem uninstall -I elasticsearch && gem install elasticsearch -v 7.17.0
# RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.3"]
# USER fluent

# FROM fluent/fluentd:v1.15-debian-1
# USER root
# RUN gem install elasticsearch -v 7.13.3
# RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.5"]
# USER fluent

FROM fluent/fluentd:v1.12.0-debian-1.0
USER root
RUN gem install elasticsearch -v 7.13.3
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.0.3"]
USER fluent