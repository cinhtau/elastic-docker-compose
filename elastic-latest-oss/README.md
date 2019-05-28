
## General

The default brings Elasticsearch and Kibana up.

If you want to use only Elasticsearch use the standalone definition.

```bash
docker-compose -f standalone up -d
```

## Data Directory

Change the `HOME_DIR` variable in `.env` for respective systems or your needs.

### Mac OS

On Mac the home directory is reserved.

```bash
sudo mkdir -p /Users/data/elasticsearch
sudo chown -R $USER:$GROUP /Users/data
```
