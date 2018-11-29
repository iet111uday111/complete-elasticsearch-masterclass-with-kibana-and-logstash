# complete-elasticsearch-masterclass-with-kibana-and-logstash
![complete-elasticsearch-masterclass-with-kibana-and-logstash](./Screenshots/Screenshot1.png?raw=true "complete-elasticsearch-masterclass-with-kibana-and-logstash")

## Description 

Elasticsearch is the biggest player in the big-data space since Hadoop. I would actually vouch that it's the Hadoop killer!

It's just now beginning to gain recognition and wider adoption in the no-sql big-data space and Elasticsearch has come a long way since it's first release. I'm sure that by just adding Elasticsearch on your linkedin profile your going to gain the attention of various companies investing in this technology. So get excited about Elasticsearch because it is a big deal.

## Technology Used

### ElasticSearch 6

Elasticsearch is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java and is released as open source under the terms of the Apache License. Official clients are available in Java, .NET (C#), PHP, Python, Apache Groovy, Ruby and many other languages.According to the DB-Engines ranking, Elasticsearch is the most popular enterprise search engine followed by Apache Solr, also based on Lucene.

Elasticsearch is developed alongside a data-collection and log-parsing engine called Logstash, and an analytics and visualisation platform called Kibana. The three products are designed for use as an integrated solution, referred to as the "Elastic Stack" (formerly the "ELK stack").

Elasticsearch can be used to search all kinds of documents. It provides scalable search, has near real-time search, and supports multitenancy."Elasticsearch is distributed, which means that indices can be divided into shards and each shard can have zero or more replicas. Each node hosts one or more shards, and acts as a coordinator to delegate operations to the correct shard(s). Rebalancing and routing are done automatically".Related data is often stored in the same index, which consists of one or more primary shards,and zero or more replica shards. Once an index has been created, the number of primary shards cannot be changed.

Elasticsearch uses Lucene and tries to make all its features available through the JSON and Java API. It supports facetting and percolating,which can be useful for notifying if new documents match for registered queries.

Another feature is called "gateway" and handles the long-term persistence of the index;[9] for example, an index can be recovered from the gateway in the event of a server crash. Elasticsearch supports real-time GET requests, which makes it suitable as a NoSQL datastore,but it lacks distributed transactions.

### Kabina 

Kibana is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

The combination of Elasticsearch, Logstash, and Kibana, referred to as the "Elastic Stack" (formerly the "ELK stack"), is available as a product or service.Logstash provides an input stream to Elasticsearch for storage and search, and Kibana accesses the data for visualizations such as dashboards

### Logstash

Logstash is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

Various Wikimedia applications send log events to Logstash, which gathers the messages, converts them into json documents, and stores them in an Elasticsearch cluster. Wikimedia uses Kibana as a front-end client to filter and display messages from the Elasticsearch cluster.


### Screenshots


#### ElasticSearch
![Screenshot](./Screenshots/Screenshot2.png?raw=true "Screenshot")
