# elasticsearch docker image

Dockerfile for [elasticsearch][elasticsearch].

It is a docker image for elasticsearch for v2.2.0 available on [docker hub][dockerhubpage]

## Usage

Get it:

    docker pull mehedikhan/elasticsearch

Run it:

    docker run -p 9200:9200 -d --name elasticsearch mehedikhan/elasticsearch
    docker run --name elasticsearch -p 9200:9200 -v /path/to/your/elasticsearch/data:/usr/share/elasticsearch/data -d mehedikhan/elasticsearch      





  [elasticsearch]: https://www.elastic.co/ "MailCatcher fake SMTP server with web interface" 
  [dockerhubpage]: https://hub.docker.com/r/mehedikhan/elasticsearch/ "Mailcatcher docker hub page"