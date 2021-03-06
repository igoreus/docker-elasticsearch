# ElasticSearch

Elasticsearch is a search server based on Lucene. It provides a distributed, multitenant-capable full-text search engine with a RESTful web interface and schema-free JSON documents.

Supported tags and respective README/Dockerfile links.

* `1.7` ([README](1.7/README.md)) ([Dockerfile](1.7/Dockerfile))
* `2.1` ([README](2.1/README.md)) ([Dockerfile](2.1/Dockerfile))

## Quickstart

```
docker run --publish 9200:9200 quay.io/trackmaven/elasticsearch:2.1.2
```

## Release checklist

Deployment to `quay.io` is handled by CirleCI.
If a version bump, update the release script in the circle.yml