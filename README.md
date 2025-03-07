﻿# Awesome-Database [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of amazingly awesome database libraries, and resources.

## Contents

- [SQL](#sql)
- [NoSQL](#nosql)
- [Key-Value](#key-value)
- [Graph](#graph)
- [Vector](#vector)
- [Research Papers](#research-papers)
- [Contribute](#contribute)

## SQL

- [Citus](https://github.com/citusdata/cstore_fdw) - Fast columnar store for analytics with PostgreSQL.
- [Facebook MySQL](https://github.com/facebook/mysql-5.6) - Facebook's branch of the Oracle MySQL v5.6 database.
- [Twitter MySQL](https://github.com/twitter/mysql) - MySQL fork maintained and used at Twitter.
- [PostgreSQL](https://github.com/postgres/postgres) - An advanced open-source relational database known for its extensibility, standards compliance, and robustness. Supports both SQL and JSON querying.
- [SQLite](http://www.sqlite.org/) - A completely embedded, full-featured relational database in a few 100k that you can include right into your project.
- [VoltDB](https://github.com/VoltDB/voltdb/) - VoltDB is a horizontally-scalable, in-memory SQL RDBMS designed for applications that have extremely high read and write throughput requirements.
- [Datomic](http://www.datomic.com/) - A distributed database designed to enable scalable, flexible, and intelligent applications, running on next-gen cloud architectures. It provides ACID transactions, joins, and a powerful query language with time-travel capabilities.
- [Cassandra](https://github.com/apache/cassandra) - Cassandra is a partitioned row store. Rows are organized into tables with a required primary key.
- [TiDB](https://www.pingcap.com/tidb) - TiDB is a full open-source MySQL _compatible_ distributed relational "NewSQL" database written in Go and Rust. Offering support for both on-premise and cloud deployments with a non-blocking DDL.
- [Greenplum](https://greenplum.org) - Greenplum is an MPP (massively parallel processing / multi-node) version of PostgreSQL, for analytic workloads. It lags behind upstream PostgreSQL versions, based on v9.4 as of June 2023.

## NoSQL

- [Aerospike](https://github.com/aerospike/aerospike-server) - Aerospike Database Server – flash-optimized, in-memory, NoSQL database.
- [MongoDB](https://github.com/mongodb/mongo) - A source-available NoSQL database program that uses a document-oriented database model. It supports a variety of data forms including text, images, and complex objects. Known for its scalability and flexibility.
- [InfluxDB](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
- [LedisDB](https://github.com/siddontang/ledisdb) - Ledisdb is a high-performance NoSQL like Redis based on LevelDB.
- [Tiedot](https://github.com/HouzuoGuo/tiedot) - A NoSQL database powered by Golang. It has a JSON API and supports basic CRUD operations and in-place updates. Designed for simplicity and performance.
- [Elasticsearch](https://github.com/elasticsearch/elasticsearch) - Open Source, Distributed, RESTful Search Engine.
- [MapDB](https://github.com/jankotek/MapDB) - MapDB provides concurrent Maps, Sets, and Queues backed by disk storage or off-heap-memory. It is a fast and easy-to-use embedded Java database engine.
- [OrientDB](https://github.com/orientechnologies/orientdb) - OrientDB is an Open Source NoSQL DBMS with the features of both Document and Graph DBMSs.
- [CouchDB](https://github.com/apache/couchdb) - Apache CouchDB™ is a database that uses JSON for documents, JavaScript for MapReduce indexes, and regular HTTP for its API.
- [Fireproof](https://github.com/fireproof-storage/fireproof) - Zero dependency, offline-capable CRDT database, runs in the browser and connects to any cloud.

## Key-Value

- [LMDB](http://symas.com/mdb/) - Very fast embedded key/value store with full ACID semantics.
- [Memcache](https://github.com/memcached/memcached) - Free & open source, high-performance, distributed memory object caching system.
- [Monetdb](https://github.com/snaga/monetdb) - An open-source column-oriented database management system that focuses on high performance for complex queries. It's often used for data warehousing, OLAP, and data mining.
- [Redis](https://github.com/antirez/redis) - Redis is an in-memory database that persists on disk. The data model is key-value, but many different kinds of values are supported: Strings, Lists, Sets, Sorted Sets, and Hashes.
- [RethinkDB](https://github.com/rethinkdb/rethinkdb) - An open-source distributed JSON document database with a pleasant and powerful query language.
- [RocksDB](https://github.com/facebook/rocksdb) - Embedded key-value store for fast storage.
- [TiKV](https://tikv.org/) - ACID-compliant, distributed key-value store, based on RocksDB. TiKV is designed as the row-based storage engine for TiDB.
- [SSDB](https://github.com/ideawu/ssdb) - SSDB - A fast NoSQL database, an alternative to Redis.
- [Riak](https://github.com/basho/riak) - Riak is a decentralized datastore from Basho Technologies.
- [Bolt](https://github.com/boltdb/bolt) - A low-level key/value database for Go.
- [Diskv](https://github.com/peterbourgon/diskv) - A home-grown disk-backed key-value store.
- [Go-cache](https://github.com/pmylund/go-cache) - An in-memory key-value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
- [GoLevelDB](https://github.com/syndtr/goleveldb) - An implementation of the [LevelDB](https://code.google.com/p/leveldb/) key/value database in the Go.
- [Groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
- [Roshi](https://github.com/soundcloud/roshi/) - Roshi is a large-scale CRDT set implementation for timestamped events.
- [Lmdbjni](https://github.com/deephacks/lmdbjni) - LMDB for Java, which is a very fast embedded key/value store with full ACID semantics.
- [HollowDB](https://github.com/firstbatchxyz/hollowdb) - HollowDB is a decentralized & privacy-preserving key-value database on the Arweave network, powered by Warp Contracts.

## Graph

- [Neo4j](https://github.com/neo4j/neo4j) - An open-source, NoSQL, native graph database that provides an ACID-compliant transactional backend for your applications. Known for its high performance, scalability, and flexibility.

## Vector

- [Pinecone](https://www.pinecone.io/) - The vector database for machine learning applications. Build vector-based personalization, ranking, and search systems that are accurate, fast, and scalable.
- [DANNY](https://github.com/firstbatchxyz/danny) - DANNY is a decentralized vector database for building vector search applications powered by Warp Contracts on the Arweave network. Offers a robust set of tools for the development of various applications, including recommendation systems and semantic search functionalities.

## Research Papers

- [DB-Readings](https://github.com/rxin/db-readings) - A list of papers essential to understanding databases and building new data systems.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
