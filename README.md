# docker logging to elasticsearch using filebeat

This example belongs to [this](https://blog.hendricksen.dev/2020/09/29/docker-logging-using-filebeat/) article from my blog.

## Usage

1. Run it by executing `docker-compose up -d`
1. After a while, log output from the elasticsearch and kibana containers will end up in elasticsearch with the help of filebeat, after which you can view the output using [kibana](http://localhost:5601).
