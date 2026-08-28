# Awesome Go Storage with stars

A curated list of awesome Go storage projects and libraries. Inspired by [awesome-go](https://github.com/avelino/awesome-go) ⭐ 182,455 | 🐛 218 | 🌐 Go | 📅 2026-08-27.

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/gostor/awesome-go-storage/blob/master/CONTRIBUTING.md) ⭐ 4,726 | 🐛 8 | 📅 2024-12-25 first. Thanks to all [contributors](https://github.com/gostor/awesome-go-storage/graphs/contributors) ⭐ 4,726 | 🐛 8 | 📅 2024-12-25; you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

* [Awesome Go Storage](#awesome-go-storage)
  * [Storage Server](#storage-server)
  * [Key-Value Store](#key-value-store)
  * [File System](#file-system)
  * [Database](#database)
  * [Database Drivers](#database-drivers)

## Storage Server

*Storage Servers implemented in Go.*

* [minio](https://github.com/minio/minio) ⚠️ Archived - Minio is an open source object storage server compatible with Amazon S3 APIs.
* [rclone](https://github.com/ncw/rclone) ⭐ 59,422 | 🐛 1,242 | 🌐 Go | 📅 2026-08-27 - "rsync for cloud storage" - Google Drive, Amazon Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Cloudfile…
* [rook](https://github.com/rook/rook) ⭐ 13,616 | 🐛 128 | 🌐 Go | 📅 2026-08-27 - Open, Cloud Native, and Universal Distributed Storage.
* [perkeep](https://github.com/perkeep/perkeep) ⭐ 7,230 | 🐛 413 | 🌐 Go | 📅 2026-02-01 - Perkeep is your personal storage system for life: a way of storing, syncing, sharing, modelling and backing up content.
* [storj](https://github.com/storj/storj) ⭐ 3,275 | 🐛 360 | 🌐 Go | 📅 2026-08-27 - Decentralized cloud object storage that is affordable, easy to use, private, and secure.
* [s3git](https://github.com/s3git/s3git) ⭐ 1,461 | 🐛 20 | 🌐 Go | 📅 2016-08-02 - Git for Cloud Storage. Distributed Version Control for Data.
* [longhorn](https://github.com/rancher/longhorn) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-08-27 - Longhorn is an open source persistent block storage server delivered via containers.

## Key-Value Store

*Key-Value Store implemented in Go.*

* [etcd](https://github.com/coreos/etcd) ⭐ 52,193 | 🐛 329 | 🌐 Go | 📅 2026-08-27 - Distributed reliable key-value store for the most critical data of a distributed system.
* [consul](https://github.com/hashicorp/consul) ⭐ 30,045 | 🐛 1,419 | 🌐 Go | 📅 2026-08-27 - Distributed consistent replicated key-value store for service discovery and configuration.
* [BadgerDB](https://github.com/dgraph-io/badger) ⭐ 15,761 | 🐛 68 | 🌐 Go | 📅 2026-08-27 - BadgerDB is an embeddable, persistent, simple and fast key-value (KV) database written in pure Go. It's meant to be a performant alternative to non-Go-based key-value stores like RocksDB.
* [go-cache](https://github.com/patrickmn/go-cache) ⭐ 8,844 | 🐛 77 | 🌐 Go | 📅 2023-11-20 - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [rosedb](https://github.com/roseduan/rosedb) ⭐ 4,886 | 🐛 7 | 🌐 Go | 📅 2026-02-10 - A fast, stable and embedded k-v database in pure Golang, supports string, list, hash, set, sorted set.
* [nutsdb](https://github.com/xujiajun/nutsdb) ⭐ 3,576 | 🐛 51 | 🌐 Go | 📅 2026-08-09 - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
* [LotusDB](https://github.com/flower-corp/lotusdb) ⭐ 2,256 | 🐛 15 | 🌐 Go | 📅 2026-08-27 - Fast k/v storage compatible with lsm tree and b+tree.
* [column](https://github.com/kelindar/column) ⭐ 1,512 | 🐛 26 | 🌐 Go | 📅 2025-06-28 - Embeddable, columnar, in-memory store with bitmap indexing, transaction and zero-alloc quering.
* [diskv](https://github.com/peterbourgon/diskv) ⭐ 1,455 | 🐛 8 | 🌐 Go | 📅 2021-11-10 - A disk-backed key-value store.
* [pogreb](https://github.com/akrylysov/pogreb) ⭐ 1,351 | 🐛 15 | 🌐 Go | 📅 2026-04-06 - Embedded key-value store for read-heavy workloads.
* [IceFireDB](https://github.com/IceFireDB/IceFireDB) ⭐ 1,154 | 🐛 7 | 🌐 Go | 📅 2026-08-24 - Distributed disk storage database using the Raft and Redis protocols.
* [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
* [Bitraft](https://git.mills.io/prologic/bitraft) - Bitraft is a distributed raft-based key/value store with a Redis-compatible protocol. It uses [Bitcask](https://git.mills.io/prologic/bitcask) for high performance/throughout and low latency.

## File System

*File Systems implemented in Go.*

* [git-lfs](https://github.com/git-lfs/git-lfs) ⭐ 14,445 | 🐛 483 | 🌐 Go | 📅 2026-08-27 - Git extension for versioning large files.
* [juicefs](https://github.com/juicedata/juicefs) ⭐ 14,366 | 🐛 195 | 🌐 Go | 📅 2026-08-27 - A distributed POSIX file system built on top of Redis and S3.
* [fsnotify](https://github.com/fsnotify/fsnotify) ⭐ 10,772 | 🐛 41 | 🌐 Go | 📅 2026-05-11 - Cross-platform file system notifications for Go.
* [afero](https://github.com/spf13/afero) ⭐ 6,693 | 🐛 128 | 🌐 Go | 📅 2026-08-14 - A FileSystem Abstraction System for Go
* [goofys](https://github.com/kahing/goofys) ⭐ 5,564 | 🐛 293 | 🌐 Go | 📅 2024-07-18 - A high-performance, POSIX-ish Amazon S3 file system written in Go.
* [minikeyvalue](https://github.com/geohot/minikeyvalue) ⭐ 3,155 | 🐛 18 | 🌐 Go | 📅 2024-02-10 - A \~1000 line distributed key value store.
* [go-systemd](https://github.com/coreos/go-systemd) ⭐ 2,711 | 🐛 65 | 🌐 Go | 📅 2026-07-23 - Go bindings to systemd socket activation, journal, D-Bus, and unit files.
* [gcsfuse](https://github.com/GoogleCloudPlatform/gcsfuse) ⭐ 2,304 | 🐛 283 | 🌐 Go | 📅 2026-08-27 - A user-space file system for interacting with Google Cloud Storage.
* [svfs](https://github.com/ovh/svfs) ⚠️ Archived - A virtual file system over Openstack Swift built upon fuse.
* [seaweedfs](https://github.com/chrislusf/seaweedfs) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2026-07-21 - SeaweedFS is a simple and highly scalable distributed file system for small files.

## Database

*Databases implemented in Go.*

* [prometheus](https://github.com/prometheus/prometheus) ⭐ 65,863 | 🐛 888 | 🌐 Go | 📅 2026-08-27 - Monitoring system and time series database.
* [tidb](https://github.com/pingcap/tidb) ⭐ 40,477 | 🐛 6,839 | 🌐 Go | 📅 2026-08-28 - TiDB is a distributed SQL database. Inspired by the design of Google F1.
* [cockroach](https://github.com/cockroachdb/cockroach) ⭐ 32,429 | 🐛 8,343 | 🌐 Go | 📅 2026-08-26 - A Scalable, Geo-Replicated, Transactional Datastore
* [influxdb](https://github.com/influxdb/influxdb) ⭐ 31,723 | 🐛 2,157 | 🌐 Rust | 📅 2026-08-25 - Scalable datastore for metrics, events, and real-time analytics
* [dolt](https://github.com/dolthub/dolt) ⭐ 24,286 | 🐛 704 | 🌐 Go | 📅 2026-08-27 - A MySQL-compatible database with Git-style version control. The first SQL database you can branch and merge.
* [dgraph](https://github.com/dgraph-io/dgraph) ⭐ 21,780 | 🐛 96 | 🌐 Go | 📅 2026-08-27 - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [rqlite](https://github.com/rqlite/rqlite) ⭐ 17,707 | 🐛 84 | 🌐 Go | 📅 2026-08-25 - The lightweight, distributed, relational database built on SQLite.
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 17,604 | 🐛 781 | 🌐 Go | 📅 2026-08-27 - Time series database designed for monitoring, compatible with PromQL (from Promethueus) and InfluxQL (from Influxdb).
* [bolt](https://github.com/boltdb/bolt) ⚠️ Archived - A low-level key/value database for Go. This original version by Ben Johnson has been marked as unmaintained and forked by [etcd-io bbolt](https://github.com/etcd-io/bbolt) ⭐ 9,706 | 🐛 30 | 🌐 Go | 📅 2026-08-26.
* [groupcache](https://github.com/golang/groupcache) ⭐ 13,335 | 🐛 45 | 🌐 Go | 📅 2024-11-29 - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [Tile38](https://github.com/tidwall/tile38) ⭐ 9,717 | 🐛 162 | 🌐 Go | 📅 2026-08-07 - A geolocation DB with spatial index and realtime geofencing.
* [immudb](https://github.com/codenotary/immudb) ⭐ 9,024 | 🐛 104 | 🌐 Go | 📅 2026-08-24 - Database with built-in cryptographic proof and verification. Can operate as a key-value store or as relational database (SQL).
* [go-cache](https://github.com/pmylund/go-cache) ⭐ 8,844 | 🐛 77 | 🌐 Go | 📅 2023-11-20 - An in-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [BigCache](https://github.com/allegro/bigcache) ⭐ 8,157 | 🐛 94 | 🌐 Go | 📅 2026-08-17 - Efficient key/value cache for gigabytes of data.
* [noms](https://github.com/attic-labs/noms) ⚠️ Archived - The versioned, forkable, syncable database.
* [SpiceDB](https://github.com/authzed/spicedb) ⭐ 6,991 | 🐛 146 | 🌐 Go | 📅 2026-08-27 - A [Zanzibar](https://research.google/pubs/pub48190/)-inspired database that stores, computes, and validates application permissions with support for multiple database backends.
* [goleveldb](https://github.com/syndtr/goleveldb) ⭐ 6,324 | 🐛 111 | 🌐 Go | 📅 2024-05-14 - An implementation of the [LevelDB](https://github.com/google/leveldb) ⭐ 39,366 | 🐛 402 | 🌐 C++ | 📅 2026-03-11 key/value database in the Go.
* [buntdb](https://github.com/tidwall/buntdb) ⭐ 4,864 | 🐛 32 | 🌐 Go | 📅 2026-05-19 - A fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
* [pREST](https://github.com/nuveo/prest) ⭐ 4,610 | 🐛 153 | 🌐 Go | 📅 2026-08-21 - Serve a RESTful API from any PostgreSQL database.
* [ledisdb](https://github.com/siddontang/ledisdb) ⭐ 4,115 | 🐛 1 | 🌐 Go | 📅 2023-10-22 - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [emitter](https://github.com/emitter-io/emitter) ⭐ 4,005 | 🐛 16 | 🌐 Go | 📅 2026-04-29 - Scalable, low-latency, distributed & secure pub/sub database with time-series message storage, suitable for IoT, gaming, apps and real-time web.
* [godis](https://github.com/hdt3213/godis) ⭐ 3,833 | 🐛 20 | 🌐 Go | 📅 2025-09-14 - A Golang implemented high-performance Redis server and cluster
* [GCache](https://github.com/bluele/gcache) ⭐ 2,731 | 🐛 30 | 🌐 Go | 📅 2024-03-01 - Cache library with support for expirable Cache, LFU, LRU and ARC.
* [tiedot](https://github.com/HouzuoGuo/tiedot) ⭐ 2,725 | 🐛 27 | 🌐 Go | 📅 2021-09-05 - Your NoSQL database powered by Golang.
* [cache2go](https://github.com/muesli/cache2go) ⭐ 2,152 | 🐛 35 | 🌐 Go | 📅 2024-07-02 - An in-memory key:value cache which supports automatic invalidation based on timeouts.
* [frostdb](https://github.com/polarsignals/frostdb/) ⭐ 1,544 | 🐛 18 | 🌐 Go | 📅 2026-08-26 - Embeddable column database written in Go.
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) ⭐ 1,528 | 🐛 36 | 🌐 Go | 📅 2023-02-25 - A SQL Database with Blockchain features.
* [diskv](https://github.com/peterbourgon/diskv) ⭐ 1,455 | 🐛 8 | 🌐 Go | 📅 2021-11-10 - A home-grown disk-backed key-value store.
* [objectbox-go](https://github.com/objectbox/objectbox-go) ⭐ 1,273 | 🐛 19 | 🌐 Go | 📅 2025-03-12 - Embedded Object Database (NoSQL) with Go API.
* [eliasdb](https://github.com/krotik/eliasdb) ⭐ 1,035 | 🐛 14 | 🌐 Go | 📅 2026-08-25 - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
* [moss](https://github.com/couchbase/moss) ⭐ 1,015 | 🐛 46 | 🌐 Go | 📅 2026-07-23 - Moss is a simple LSM key-value storage engine written in 100% Go.
* [clover](https://github.com/ostafen/clover) ⭐ 832 | 🐛 19 | 🌐 Go | 📅 2025-09-09 - A lightweight document-oriented NoSQL database written in pure Golang.
* [levigo](https://github.com/jmhodges/levigo) ⭐ 421 | 🐛 6 | 🌐 Go | 📅 2022-03-07 - Levigo is a Go wrapper for LevelDB.
* [piladb](https://github.com/fern4lvarez/piladb) ⭐ 206 | 🐛 10 | 🌐 Go | 📅 2025-12-05 - Lightweight RESTful database engine based on stack data structures.
* [scribble](https://github.com/nanobox-io/golang-scribble) ⭐ 176 | 🐛 1 | 🌐 Go | 📅 2019-03-09 - A tiny flat file JSON store.
* [geocache](https://github.com/melihmucuk/geocache) ⭐ 141 | 🐛 0 | 🌐 Go | 📅 2016-06-21 - An in-memory cache that is suitable for geolocation based applications.
* [couchcache](https://github.com/codingsince1985/couchcache) ⭐ 63 | 🐛 1 | 🌐 Go | 📅 2024-06-16 - A RESTful caching micro-service backed by Couchbase server.
* [forestdb](https://github.com/couchbase/goforestdb) ⭐ 36 | 🐛 7 | 🌐 Go | 📅 2016-12-15 - Go bindings for ForestDB.

*Database schema migration.*

* [migrate](https://github.com/golang-migrate/migrate) ⭐ 18,858 | 🐛 489 | 🌐 Go | 📅 2026-07-05 - Database migration handling in Golang support MySQL, PostgreSQL, Cassandra, and SQLite.
* [sql-migrate](https://github.com/rubenv/sql-migrate) ⭐ 3,419 | 🐛 98 | 🌐 Go | 📅 2026-07-14 - Database migration tool. Allows embedding migrations into the application using go-bindata.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) ⭐ 1,172 | 🐛 17 | 🌐 Go | 📅 2026-05-26 - Database schema migration helper for Gorm ORM.
* [darwin](https://github.com/GuiaBolso/darwin) ⭐ 150 | 🐛 5 | 🌐 Go | 📅 2023-02-24 - Database schema evolution library for Go
* [goose](https://github.com/steinbacher/goose) ⚠️ Archived - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
* [pravasan](https://github.com/pravasan/pravasan) ⭐ 30 | 🐛 30 | 🌐 HTML | 📅 2018-12-20 - Simple Migration tool - currently for MySQL but planning to support soon for Postgres, SQLite, MongoDB, etc.,
* [soda](https://github.com/markbates/pop/tree/master/soda) ⭐ 7 | 🐛 0 | 📅 2019-11-26 - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.

*Database tools.*

* [vitess](https://github.com/youtube/vitess) ⭐ 21,266 | 🐛 1,097 | 🌐 Go | 📅 2026-08-28 - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.
* [usql](https://github.com/xo/usql) ⭐ 10,090 | 🐛 118 | 🌐 Go | 📅 2026-06-19 - universal command-line interface for SQL databases
* [pgweb](https://github.com/sosedoff/pgweb) ⭐ 9,488 | 🐛 55 | 🌐 Go | 📅 2026-07-26 - A web-based PostgreSQL database browser
* [kingshard](https://github.com/flike/kingshard) ⭐ 6,401 | 🐛 160 | 🌐 Go | 📅 2026-06-05 - kingshard is a high performance proxy for MySQL powered by Golang.
* [orchestrator](https://github.com/openark/orchestrator) ⚠️ Archived - MySQL replication topology manager & visualizer
* [go-mysql](https://github.com/siddontang/go-mysql) ⭐ 4,962 | 🐛 157 | 🌐 Go | 📅 2026-08-23 - A go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) ⭐ 4,148 | 🐛 219 | 🌐 Go | 📅 2023-10-22 - Sync your MySQL data into Elasticsearch automatically.
* [myreplication](https://github.com/2tvenom/myreplication) ⭐ 193 | 🐛 5 | 🌐 Go | 📅 2018-10-05 - MySql binary log replication listener. Support statement and row based replication.

*SQL query builder, libraries for building and using SQL.*

* [Squirrel](https://github.com/Masterminds/squirrel) ⭐ 7,980 | 🐛 96 | 🌐 Go | 📅 2024-04-24 - Go library that helps you build SQL queries.
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) ⭐ 6,991 | 🐛 107 | 🌐 Go | 📅 2026-07-12 - a tool to generate a Go ORM tailored to your database schema. It is a "database-first" ORM as opposed to "code-first", and you must first create your database.
* [xo](https://github.com/knq/xo) ⭐ 3,894 | 🐛 68 | 🌐 Go | 📅 2026-08-04 - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.
* [goqu](https://github.com/doug-martin/goqu) ⭐ 2,671 | 🐛 146 | 🌐 Go | 📅 2024-05-22 - An idiomatic SQL builder and query library.
* [Dotsql](https://github.com/gchaincl/dotsql) ⭐ 740 | 🐛 8 | 🌐 Go | 📅 2023-11-24 - Go library that helps you keep sql files in one place and use it with ease.
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) ⭐ 670 | 🐛 23 | 🌐 Go | 📅 2026-08-25 - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
* [dat](https://github.com/mgutz/dat) ⭐ 610 | 🐛 25 | 🌐 Go | 📅 2020-10-25 - Go Postgres Data Access Toolkit
* [sqrl](https://github.com/elgris/sqrl) ⭐ 286 | 🐛 8 | 🌐 Go | 📅 2023-06-15 - SQL query builder, fork of Squirrel with improved performance.
* [buildsqlx](https://github.com/arthurkushman/buildsqlx) ⭐ 188 | 🐛 8 | 🌐 Go | 📅 2026-06-21 - Go Database query builder library
* [grimoire](https://github.com/Fs02/grimoire) ⭐ 161 | 🐛 0 | 🌐 Go | 📅 2021-10-25 - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
* [igor](https://github.com/galeone/igor) ⭐ 128 | 🐛 0 | 🌐 Go | 📅 2024-04-14 - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
  * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) ⭐ 15,273 | 🐛 73 | 🌐 Go | 📅 2026-08-27 - MySQL driver for Go.
  * [pgx](https://github.com/jackc/pgx) ⭐ 14,190 | 🐛 251 | 🌐 Go | 📅 2026-08-24 - PostgreSQL driver supporting features beyond those exposed by database/sql.
  * [pq](https://github.com/lib/pq) ⭐ 9,951 | 🐛 52 | 🌐 Go | 📅 2026-08-20 - Pure Go Postgres driver for database/sql.
  * [go-sqlite3](https://github.com/mattn/go-sqlite3) ⭐ 9,228 | 🐛 159 | 🌐 C | 📅 2026-08-17 - SQLite3 driver for go that using database/sql.
  * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) ⭐ 1,883 | 🐛 177 | 🌐 Go | 📅 2025-04-26 - Microsoft MSSQL driver in go language.
  * [go-oci8](https://github.com/mattn/go-oci8) ⭐ 631 | 🐛 3 | 🌐 Go | 📅 2026-07-08 - Oracle driver for go that using database/sql.
  * [firebirdsql](https://github.com/nakagami/firebirdsql) ⭐ 266 | 🐛 0 | 🌐 Go | 📅 2026-08-19 - Firebird RDBMS SQL driver for Go
  * [go-adodb](https://github.com/mattn/go-adodb) ⭐ 154 | 🐛 18 | 🌐 Go | 📅 2026-07-10 - Microsoft ActiveX Object DataBase driver for go that using database/sql.
  * [go-bqstreamer](https://github.com/rounds/go-bqstreamer) ⚠️ Archived - BigQuery fast and concurrent stream insert.
  * [gofreetds](https://github.com/minus5/gofreetds) ⭐ 114 | 🐛 18 | 🌐 Go | 📅 2020-11-30 Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).
  * [bgc](https://github.com/viant/bgc) ⭐ 21 | 🐛 0 | 🌐 Go | 📅 2024-03-17 - Datastore Connectivity for BigQuery for go.

* NoSQL Databases
  * [redis](https://github.com/go-redis/redis) ⭐ 22,223 | 🐛 66 | 🌐 Go | 📅 2026-08-27 - Redis client for Golang
  * [cayley](https://github.com/google/cayley) ⭐ 15,062 | 🐛 93 | 🌐 Go | 📅 2026-08-27 - A graph database with support for multiple backends.
  * [redigo](https://github.com/gomodule/redigo) ⭐ 9,857 | 🐛 24 | 🌐 Go | 📅 2025-11-02 - Redigo is a Go client for the Redis database.
  * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) ⭐ 8,538 | 🐛 21 | 🌐 Go | 📅 2026-08-27 - The Go driver for MongoDB
  * [gomemcache](https://github.com/bradfitz/gomemcache/) ⭐ 1,883 | 🐛 49 | 🌐 Go | 📅 2026-07-12 - memcache client library for the Go programming language.
  * [gorethink](https://github.com/GoRethink/gorethink) ⭐ 1,646 | 🐛 27 | 🌐 Go | 📅 2025-10-24 - Go language driver for RethinkDB
  * [redis](https://github.com/hoisie/redis) ⭐ 583 | 🐛 15 | 🌐 Go | 📅 2016-07-30 - A simple, powerful Redis client for Go.
  * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) ⭐ 460 | 🐛 48 | 🌐 Go | 📅 2026-08-27 - Aerospike client in Go language.
  * [redeo](https://github.com/bsm/redeo) ⭐ 443 | 🐛 3 | 🌐 Go | 📅 2023-01-20 - Redis-protocol compatible TCP servers/services.
  * [neoism](https://github.com/jmcvetta/neoism) ⭐ 388 | 🐛 12 | 🌐 Go | 📅 2020-02-16 - Neo4j client for Golang
  * [gocb](https://github.com/couchbase/gocb) ⭐ 377 | 🐛 1 | 🌐 Go | 📅 2026-08-27 - Official Couchbase Go SDK
  * [go-couchbase](https://github.com/couchbase/go-couchbase) ⭐ 323 | 🐛 40 | 🌐 Go | 📅 2025-08-25 - Couchbase client in Go
  * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) ⚠️ Archived - Neo4j REST Client in golang.
  * [arangolite](https://github.com/solher/arangolite) ⭐ 72 | 🐛 5 | 🌐 Go | 📅 2021-03-10 - Lightweight golang driver for ArangoDB.
  * [go-couchdb](https://github.com/fjl/go-couchdb) ⭐ 59 | 🐛 1 | 🌐 Go | 📅 2024-04-09 - Yet another CouchDB HTTP API wrapper for Go
  * [dsc](https://github.com/viant/dsc) ⭐ 37 | 🐛 1 | 🌐 Go | 📅 2025-12-31 - Datastore connectivity for SQL, NoSQL, structured files.
  * [goriak](https://github.com/zegl/goriak) ⭐ 30 | 🐛 4 | 🌐 Go | 📅 2021-09-15 - Go language driver for Riak KV
  * [neo4j](https://github.com/cihangir/neo4j) ⭐ 29 | 🐛 8 | 🌐 Go | 📅 2015-04-02 - Neo4j Rest API Bindings for Golang
  * [asc](https://github.com/viant/asc) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2024-09-20 - Datastore Connectivity for Aerospike for go.
  * [dynago](https://github.com/underarmour/dynago) - Dynago is a principle of least surprise client for DynamoDB
  * [gocql](http://gocql.github.io) - A Go language driver for Apache Cassandra.

* Search and Analytic Databases
  * [bleve](https://github.com/blevesearch/bleve) ⭐ 11,190 | 🐛 296 | 🌐 Go | 📅 2026-08-27 - A modern text indexing library for go.
  * [elastic](https://github.com/olivere/elastic) ⭐ 7,447 | 🐛 116 | 🌐 Go | 📅 2024-08-08 - Elasticsearch client for Go.
  * [elastigo](https://github.com/mattbaird/elastigo) ⭐ 941 | 🐛 68 | 🌐 Go | 📅 2019-02-05 - A Elasticsearch client library.
  * [skizze](https://github.com/seiflotfy/skizze) - A probabilistic data-structures service and storage.

* Multiple Backends
  * [gokv](https://github.com/philippgille/gokv) ⭐ 827 | 🐛 45 | 🌐 Go | 📅 2025-11-20 - A simple key-value store interface and many implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more)
  * [Fiber Storage](https://github.com/gofiber/storage) ⭐ 335 | 🐛 2 | 🌐 Go | 📅 2026-08-27 - Premade storage drivers that implement the [Storage](https://github.com/gofiber/storage/blob/main/storage.go) ⭐ 335 | 🐛 2 | 🌐 Go | 📅 2026-08-27 interface.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
