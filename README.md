# elastic-docker-compose

Docker Compose for getting started with Elasticsearch and Kibana.

[License](LICENSE)

Check respective versions in [Past Releases](https://www.elastic.co/downloads/past-releases)

Use this as [baseline](https://github.com/elastic/elasticsearch/blob/master/distribution/docker/docker-compose.yml) for your docker-compose files.

## Elasticsearch Version 2

In the folder `elastic-v2` you will find the setup for Elasticsearch 2.4.6 and Kibana 4.6.6.

## Elasticsearch Version 5

Find the Open Source only docker-compose file in `elastic-v5-oss`.

## Latest Elasticsearch with Kibana

In the folder `elastic-latest` you find the recent version of Elasticsearch and Kibana.



Change the settings and version number in the `.env` file.

## Kibana-Only

If you have a running local Elasticsearch instance just start Kibana with Docker. 

Replace the Kibana version number with the Elasticsearch version you need. 

```bash
$ cd kibana-only
$ docker-compose up -d
```

Kibana should connect with your local elasticsearch instance. It does not use any X-Pack related security.
