# Docker Logging with Filebeat and ELK

This example belongs to [this](https://medium.com/p/6abc21a0a8f4/edit) article.

## Usage

1. Run it by executing `docker-compose up --build`
1. After a while, log output from the docker and kibana containers will end up in elasticsearch with the help of filebeat, after which you can view the output using kibana.
