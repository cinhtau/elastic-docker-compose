## General

The default brings Elasticsearch and Kibana up.

With the [license change](https://www.elastic.co/blog/licensing-change) the last version of Open Source (OSS) is **7.10.2**.

If you want to use only Elasticsearch use the standalone definition.

```bash
docker-compose -f standalone up -d
```

## Data Directory

Change the `HOME_DIR` variable in `.env` for respective systems or your needs.

Update: Use Docker volumes for test, no persistent data is needed.

### Mac OS

If you still want a persistent directory. On Mac the home directory is reserved.

```bash
sudo mkdir -p /Users/data/elasticsearch
sudo chown -R $USER:$GROUP /Users/data
```
