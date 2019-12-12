# Awesome Go

[![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) financial support to Awesome Go

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot-internet-of-things)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, ABAC.
* [jwt-go](https://github.com/dgrijalva/jwt-go) - Golang implementation of JSON Web Tokens (JWT).
* [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
* [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
* [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang.
* [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).
* [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
* [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).
* [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.

## Configuration

*Libraries for configuration parsing.*

* [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
* [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
* [ini](https://github.com/go-ini/ini) - Go package to read and write INI files.
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.

## Continuous Integration

*Tools for help with continuous integration.*

* [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
* [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.

## Data Structures

*Generic datastructures and algorithms in Go.*

* [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
* [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
* [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
* [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
* [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.

## Database

*Databases implemented in Go.*

* [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
* [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
* [bolt](https://github.com/boltdb/bolt) - Low-level key/value database for Go.
* [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
* [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
* [go-cache](https://github.com/pmylund/go-cache) - In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.
* [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.
* [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
* [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
* [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
* [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
* [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
* [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.

*Database schema migration.*

* [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
* [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.

*Database tools.*

* [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
* [kingshard](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
* [orchestrator](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
* [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

*SQL query builder, libraries for building and using SQL.*

* [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
    * [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
    * [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.

* NoSQL Databases
    * [gocql](http://gocql.github.io) - Go language driver for Apache Cassandra.
    * [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
    * [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
    * [redis](https://github.com/go-redis/redis) - Redis client for Golang.

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
    * [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go.

* Multiple Backends.
    * [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends.

## Date and Time

*Libraries for working with dates and times.*

* [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
* [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang.

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
* [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
* [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
* [KrakenD](https://github.com/devopsfaith/krakend) - Ultra performant API Gateway framework with middlewares.
* [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
* [micro](https://github.com/micro/micro) - Pluggable microservice toolkit and distributed systems platform.
* [NATS](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
* [raft](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
* [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
* [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.
* [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package.

## Email

*Libraries and tools that implement email creation and sending.*

* [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
* [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
* [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [expr](https://github.com/antonmedv/expr) - an engine that can evaluate expressions.
* [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
* [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
* [otto](https://github.com/robertkrimen/otto) - JavaScript interpreter written in Go.
* [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go.

## Error Handling

*Libraries for handling errors.*

* [errors](https://github.com/pkg/errors) - Package that provides simple error handling primitives.

## Files

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.

## Forms

*Libraries for working with forms.*

* [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
* [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.

## Geographic

*Geographic tools and servers*

* [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.

## Go Compilers

*Tools for compiling Go to other languages.*

* [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
* [llgo](https://github.com/go-llvm/llgo) - LLVM-based compiler for Go.

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) - A high-performance goroutine pool for golang.
* [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
* [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang.

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
* [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go, rendered using EFL. Supports: Linux, macOS, Windows.
* [go-astilectron](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
* [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
* [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
* [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
* [walk](https://github.com/lxn/walk) - Windows application library kit for Go.
* [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

* [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
* [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package.
* [resize](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
* [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
* [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.

## Job Scheduler

*Libraries for scheduling jobs.*

* [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
* [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.

## JSON

*Libraries for working with JSON.*

* [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
* [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.

## Logging

*Libraries for generating and working with log files.*

* [glog](https://github.com/golang/glog) - Leveled execution logs for Go.
* [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go.
* [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
* [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
* [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger.

## Messaging

*Libraries that implement messaging systems.*

* [Benthos](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
* [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
* [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
* [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).
* [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
* [NATS Go Client](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and d
* [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka.

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
* [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
* [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).

### Project Layout

*Unofficial set of patterns for structuring projects.*

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem.

### Strings

*Libraries for working with strings.*

* [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

*These libraries were placed here because none of the other categories seemed to fit.*

* [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
* [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
* [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.

## Natural Language Processing

*Libraries for working with human languages.*

* [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.

## Networking

*Libraries for working with various layers of the network.*

* [dns](https://github.com/miekg/dns) - Go library for working with DNS.
* [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
* [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
* [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
* [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
* [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.
* [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
* [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.

### HTTP Clients

*Libraries for making HTTP requests.*

* [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
* [heimdall](https://github.com/gojektech/heimdall) - An enchanced http client with retry and hystrix capabilities.
* [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

* [beego orm](https://github.com/astaxie/beego/tree/master/orm) - Powerful orm framework for go. Support: pq/mysql/sqlite3.
* [go-pg](https://github.com/go-pg/pg) - PostgreSQL ORM with focus on PostgreSQL specific features and performance.
* [GORM](https://github.com/jinzhu/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
* [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
* [Xorm](https://github.com/go-xorm/xorm) - Simple and powerful ORM for Go.

## Package Management

*Official tooling for dependency and package management*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

* [dep](https://github.com/golang/dep) - Go dependency tool.

*Unofficial libraries for package and dependency management.*

* [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.

## Performance

* [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
* [profile](https://github.com/pkg/profile) - Simple profiling support package for Go.

## Query Language

* [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
* [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.

## Resource Embedding

* [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as html,js,css,images and templates very easy.
* [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
* [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable.

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

* [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
* [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
* [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
* [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
* [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.

## Security

*Libraries that are used to help make your application more secure.*

* [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
* [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
* [lego](https://github.com/xenolf/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
* [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
* [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.

## Serialization

*Libraries and tools for binary serialization.*

* [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
* [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
* [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
* [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.

## Server Applications

* [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
* [Caddy](https://github.com/mholt/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
* [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [devd](https://github.com/cortesi/devd) - Local webserver for developers.
* [etcd](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
* [minio](https://github.com/minio/minio) - Minio is a distributed object storage server.
* [SFTPGo](https://github.com/drakkan/sftpgo) - Full featured and highly configurable SFTP server software.

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

* [go-streams](https://github.com/reugn/go-streams) - Go stream processing library.

## Template Engines

*Libraries and tools for templating and lexing.*

* [ace](https://github.com/yosssi/ace) - Ace is an HTML template engine for Go, inspired by Slim and Jade. Ace is a refinement of Gold.
* [amber](https://github.com/eknkc/amber) - Amber is an elegant templating engine for Go Programming Language It is inspired from HAML and Jade.
* [hero](https://github.com/shiyanhui/hero) - Hero is a handy, fast and powerful go template engine.
* [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
* [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.

## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks
    * [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    * [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
    * [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    * [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    * [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    * [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.

* Mock
    * [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    * [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    * [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
    * [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.

* Fuzzing and delta-debugging/reducing/shrinking.
    * [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    * [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values.

* Selenium and browser control tools.
    * [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    * [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.

* Fail injection
    * [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](http://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats
    * [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go.
    * [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
    * [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
    * [github_flavored_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
    * [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
    * [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
    * [sh](https://github.com/mvdan/sh) - Shell parser and formatter.
    * [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).
* Utility
    * [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
    * [xurls](https://github.com/mvdan/xurls) - Extract urls from text.

## Third-party APIs

*Libraries for accessing third party APIs.*

* [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
* [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
* [aws-sdk-go](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
* [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
* [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
* [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
* [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
* [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
* [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
* [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
* [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
* [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
* [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
* [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
* [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
* [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
* [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](http://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](http://geocoder.opencagedata.com/api.html), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
* [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
* [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
* [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
* [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
* [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
* [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
* [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
* [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
* [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](http://myanimelist.net/modules.php?go=api).
* [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
* [go-sptrans](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
* [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
* [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
* [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
* [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
* [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
* [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
* [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
* [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](http://www.malshare.com/)
* [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
* [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
* [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
* [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
* [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
* [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
* [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
* [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
* [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
* [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
* [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](http://sourceware.org/libffi/) integration
* [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
* [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](http://mesos.apache.org/) cluster.
* [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
* [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
* [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
* [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
* [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
* [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
* [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
* [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
* [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
* [slack](https://github.com/nlopes/slack) - Slack API in Go.
* [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
* [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
* [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
* [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
* [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
* [translate](https://github.com/poorny/translate) - Go online translation package.
* [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API.
* [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
* [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
* [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
* [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
* [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
* [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
* [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
* [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

## Utilities

*General utilities and tools to make your life easier.*

* [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
* [ctop](https://github.com/bcicen/ctop) - [Top-like](http://ctop.sh) interface (e.g. htop) for container metrics.
* [delve](https://github.com/derekparker/delve) - Go debugger.
* [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
* [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamicly based on s-expression. It's simple and easy to extend.
* [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
* [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
* [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
* [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
* [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
* [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
* [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
* [hystrix-go](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
* [mmake](https://github.com/tj/mmake) - Modern Make.
* [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
* [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool.
* [realize](https://github.com/tockins/realize) - Go build system with file watchers and live reload. Run, build and watch file changes with custom paths.
* [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
* [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
* [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
* [Task](https://github.com/go-task/task) - simple "Make" alternative.
* [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
* [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.

## UUID

*Libraries for working with UUIDs.*

* [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
* [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.

## Validation

*Libraries for validation.*

* [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
* [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
* [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
* [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.

## Version Control

*Libraries for version control.*

* [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2.
* [go-git](https://github.com/src-d/go-git) - highly extensible Git implementation in pure Go.

## Video

*Libraries for manipulating video.*

* [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
* [goav](https://github.com/giorgisio/goav) - Comphrensive Go bindings for FFmpeg.
* [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.

## Web Frameworks

*Full stack web frameworks.*

* [Beego](https://github.com/astaxie/beego) - beego is an open-source, high-performance web framework for the Go programming language.
* [Buffalo](http://gobuffalo.io) - Bringing the productivity of Rails to Go!
* [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
* [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
* [Gizmo](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
* [go-json-rest](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
* [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
* [Macaron](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
* [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language.
* [utron](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).

### Middlewares

#### Actual middlewares

* [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
* [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
* [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
* [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.

#### Libraries for creating HTTP middlewares

* [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go.
* [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
* [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.

### Routers

* [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
* [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
* [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
* [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go.
* [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
* [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.

## Windows

* [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.

# Tools

*Go software and plugins.*

## Code Analysis

* [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
* [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
* [lint](https://github.com/surullabs/lint) - Run linters as part of go test.
* [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.

## Editor Plugins

* [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
* [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
* [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
* [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
* [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
* [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
* [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
* [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
* [theia-go-extension](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
* [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
* [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim.
* [vscode-go](https://github.com/Microsoft/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
* [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

## Go Generate Tools

* [genny](https://github.com/cheekybits/genny) - Elegant generics for Go.
* [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code.

## Go Tools

* [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
* [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
* [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.

## Software Packages

*Software written in Go.*

### DevOps Tools

* [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
* [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
* [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
* [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
* [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
* [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
* [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
* [goxc](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
* [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
* [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
* [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
* [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
* [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
* [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
* [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
* [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
* [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
* [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.

### Other Software

* [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
* [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
* [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
* [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
* [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
* [Docker](http://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
* [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
* [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
* [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
* [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
* [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
* [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
* [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
* [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
* [restic](https://github.com/restic/restic) - De-duplicating backup program.
* [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
* [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
* [snap](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
* [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
* [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.

# Resources

*Where to discover new Go libraries.*

## Benchmarks

* [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
* [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
* [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
* [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
* [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
* [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
* [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
* [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
* [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
* [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
* [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
* [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

## E-Books

* [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
* [An Introduction to Programming in Go](http://www.golang-book.com/)
* [Build Web Application with Golang](https://www.gitbook.com/book/astaxie/build-web-application-with-golang/details)
* [Building Web Apps With Go](https://www.gitbook.com/book/codegangsta/building-web-apps-with-go/details)
* [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
* [Go Bootcamp](http://golangbootcamp.com)
* [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian.
* [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books.
* [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
* [Network Programming With Go](https://jan.newmarch.name/go/)
* [The Go Programming Language](http://www.gopl.io/)
* [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
* [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)
* [Writing A Compiler In Go](https://compilerbook.com)
* [Writing An Interpreter In Go](https://interpreterbook.com)

### Tutorials

* [50 Shades of Go](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
* [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
* [A Tour of Go](http://tour.golang.org/) - Interactive tour of Go.
* [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
* [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
* [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
* [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
* [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
* [Games With Go](http://gameswithgo.org/) - A video series teaching programming and game development.
* [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
* [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
* [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
* [Go Playground for iOS](https://itunes.apple.com/us/app/go-playground/id1437518275?ls=1&mt=8) - Interactively edit & play Go snippets on your mobile device.
* [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
* [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
* [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
* [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
* [GolangCode](https://golangcode.com/) - Collection of code snippets and tutorials to help tackle every day issues.
* [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
* [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
* [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
* [Learning Golang - From zero to hero](https://milapneupane.com.np/2019/07/06/learning-golang-from-zero-to-hero/) - Getting started with golang for beginner.
* [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
* [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
* [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
* [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
* [Your basic Go](http://yourbasic.org/golang) - Huge collection of tutorials and how to's.
