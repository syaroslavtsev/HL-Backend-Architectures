HL-Backend-Architectures
========================

High Load Backend Architectures

## [Twitter]( http://goo.gl/8z33 )

ror, scala, jetty, erlang, thrift, mongrel, comet server, my-sql, memchached, varnish, kestrel(mq), starling, gizzard, cassandra, hadoop, vertica, munin, nagios, awstats

* [Introduce Gizzard of Twitter - 트위터의 새로운 분산 관리 라이브러리 Gizzard를 소개합니다.]( http://goo.gl/yhXdn )
* [The Architecture Twitter Uses to Deal with 150M Active Users, 300K QPS, a 22 MB/S Firehose, and Send Tweets in Under 5 Seconds]( http://goo.gl/34fVo )
* [Scaling Twitter: Making Twitter 10000 Percent Faster]( http://goo.gl/8z33 )
* [Scaling Twitter]( http://goo.gl/bqvCW )
* [Blaine Cook on Scaling Twitter - YouTube]( http://goo.gl/SAHoj )
* [How Twitter Stores 250 Million Tweets a Day Using MySQL]( http://goo.gl/9Fulp ) ([Korean]( http://goo.gl/thjIs ))
* [Twitter on Scala]( http://goo.gl/IW1D )
* [DataSift Architecture: Realtime Datamining at 120,000 Tweets Per Second]( http://goo.gl/crijI )
* [Improving Running Components at Twitter]( http://goo.gl/q7EXg )
* [QCon London 2009: Upgrading Twitter without service disruptions]( http://goo.gl/qbI2 )

## [Facebook]( http://goo.gl/QVFM )

php (with hiphop compiler), thrift, java(tomcat, jetty, minor), epoll, erlang, tornado, nodejs my-sql, memcahced, hadoop, hbase, hive, scribe(-hdfs), bigpipe, varnish, haystack, cassandra

* ["Building for a Billion Users" - YouTube]( http://goo.gl/nfwqD )
* [Scaling Out]( http://goo.gl/LqExb )
* [Facebook Architecture - Stack Overflow]( http://goo.gl/KRJ5s )
* [Facebook Architecture for 600M users]( http://goo.gl/Rb2Ae )
* [Facebook Chat]( http://goo.gl/Vl4ey )
* [Scaling the Messages Application Back End]( http://goo.gl/I9QMr )
* [Facebook's New Realtime Analytics System: HBase to Process 20 Billion Events Per Day]( http://goo.gl/GHHAF )

## [Tumblr]( http://goo.gl/CrC0P ) ([Korean]( http://goo.gl/rxgNV ))

centos, sciapache, apache, nginx, (move out of)php, scala(selection), ruby, thrift, my-sql, redis, hbase, memcached, gearman, kafka, kestrel, finagle, varnish, ha-proxy, func, capistrano, puppet, jenkins

* [Evan Ellis "Tumblr. Massively Sharded MySQL"]( http://goo.gl/J7OAy )
* 
## [Quora]( http://rapapa.net/?p=156 )

aws(ec2, s3), ubuntu, cloudfront, python, pylons, paste, tornado, thrift, comet server, memcached, haproxy, nginx

## [Pinterest]( http://goo.gl/lUFBZ )

python, django, tornado, node.js, rabbitmq, nginx, haproxy, varnish, memcached, membase, redis, my-sql, mrjob, hadoop(elastic map reduce)

* [Pinterest Architecture Update - 18 Million Visitors, 10x Growth,12 Employees, 410 TB of Data]( http://goo.gl/D8oqg )
* [Polyglot persistence at Pinterest: Redis, Membase, MySQL • myNoSQL]( http://goo.gl/Yl8WX )

## [Instagram]( http://goo.gl/2mxW7 ) ([Korean]( http://goo.gl/lP9T5 ))

aws(s3, ebs), cloudfront, ubuntu, django(high-cpu extra-large), gunicorn, fabric, gearman, pyapns, twisted, postgre-sql(quadruple extra-large), mdadm(sofeware raid with ebs), repmgr, pgbouncer, redis, memcached, node2dm, munin, pingdom, pagerduty, sentry

* [Instagram Architecture Update: What’s new with Instagram?]( http://goo.gl/xpPac )
* [What Powers Instagram: Hundreds of Instances, Dozens of Technologies - Instagram Engineering]( http://goo.gl/mkfQN ) ([Korean]( http://goo.gl/lP9T5 ))
* [Tracking Slow Requests with Dogslow]( http://goo.gl/A32kZ )
* [Keeping Instagram up with over a million new users in twelve hours - Instagram Engineering]( http://goo.gl/HvrQj )

## [Pulse]( http://goo.gl/fsFk0 )

aws(ec2, s3, elb), tornado, scribe, mrjob, node-readability, haproxy, tornado, gae, mapreduce, django(appengine), google-cloud-storage, memcache, redis

* [Backend « Pulse News Engineering Blog]( http://goo.gl/Ggszf )

## [Netflix]( http://goo.gl/4Xwo2 )

aws(ec2, s3, ebs, rds, dynamodb, sdb, sqs, sns, emr, elb, eip, vpc, direct-connect, iam), java(tomcat), mongodb, my-sql, casandra, hadoop, zookeeper, evcache, asgard, groovy, grails, zuul, priam and more [netflix opensouces)]( http://goo.gl/opocK )

* [Architectural Patterns for High Availability - Netflix]( http://goo.gl/sqo36 )
* [The Netflix Tech Blog]( http://goo.gl/JoIkO )
* [3 shades of latency: How Netflix built a data architecture around timeliness — Tech News and Analysis]( http://goo.gl/vgkJ1 )
* [Keeping Movies Running Amid Thunderstorms!]( http://goo.gl/wOaAi )

## [Spoqa]( http://goo.gl/MkRaU )

linux(2.6), nginx, uwsgi, aws(s3), dotcloud, mysql, redis, celery

## [StyleShare]( http://goo.gl/WWkPR )

ubuntu(12.04), aws(ec2, s3, elb), nginx, werkzeug, flask, postgre-sql, pgpool, memcached, gevent, celery, rabbitmq, fabric, boto, exceptional, flask-exceptional

## [Gae9(개9)]( http://goo.gl/t8n5d )

rabbitmq, celery, phash

## [TheBorn Coupon(더본쿠폰)]( http://goo.gl/KwvQP )

ubuntu(12.04), nhn ncloud, django, apache, mod_wsgi, ms-sql, memcached, fabric, south, wand, rsync, py-bcrypt, python-gcm, apns

## [Lezhin Comics(레진코믹스)](http://goo.gl/656cz)

gae, "천만명 이하 규모는 구글 앱 엔진을 써도 충분하다.([Translate](http://goo.gl/q0n1V ))" - @[xguru](https://twitter.com/xguru)

## [Cartoon Service(만화서비스) - Smartstudy]( http://goo.gl/3z2j6 )

ubuntu(11.04) nbp (nhn business platform), my-sql(innodb), mongodb, django, fabric, uwsgi, nginx, memcached, cacti, npk, rsync, lftp

## [99designs]( http://goo.gl/YSNnp )

aws(ec2, s3, elb, rds, cloudwatch), varnish, php, ergo, my-sql, memcached, mongodb, redis, new-relic, statsd

## [TripAdvisor]( http://goo.gl/1D9VM )

linux, apache, java, tomcat, postgres-sql, lucene, velocity, memcached, jgroups, hadoop, cacti, nagios, custom[?]

* supoorting infra: java, python, ruby, php, perl

## [Trello]( http://goo.gl/MzDNv )

nodejs, haproxy, redis, mongodb

## [GOV.UK]( http://goo.gl/CFQrV )

ubuntu(10.04), skyscape, akamai, puppet, puppetdb, nginx, unicorn, gunicorn, upstart, haproxy, varnish,

 * redirection: perl(manage and test), php(some), nodejs(side-by-side browser)
 * applications: ror, sinatra, scala, play(2.0), django, mapit
 * databases and other storage: mongodb, my-sql, postgres-sql, elasticsearch, solr, rabbitmq
 * monitoring, managing and alerting: statsd, logstash, ganglia, graphie, nagios
 * supporting tools: jenkins, new-relic, google-analytics, dyn, ses, font-forge, font-tools, zendesk, jekyll, heroku, clojure

## [StackExchange]( http://goo.gl/uQWcr )

windows server, sql-server, redis

* [The Stack Exchange Architecture – 2011 Edition, Episode 1 - Server Fault Blog]( http://goo.gl/dXe1g )

## [YouPorn]( http://goo.gl/rd59z )

php-frm, haproxy, activemq, varnish, redis, nginx, my-sql, syslog-ng, symfony2


## [LinkedIn]()

* [LinkedIn Data Infrastructure (QCon London 2012)]( http://goo.gl/cDHMX )

## [SoundCloud]( http://goo.gl/Mzvv4 )


## [Tagged]( http://goo.gl/B0tmR )


REFERENCES
----------

## INFRA, PLATFORMS, FRAMEWORKS

* [Amazon Web Services, Cloud Computing: Compute, Storage, Database]( http://goo.gl/HF0i )
 * [Elastic Load Balancing]( http://goo.gl/VqsP )
 * [Amazon Elastic Compute Cloud(Amazon EC2)]( http://goo.gl/qU2Xn )
 * [ELB, Elastic Load Balancing]( http://goo.gl/VqsP )
 * [Amazon Simple Storage Service (Amazon S3)]( http://goo.gl/T8ERz )
 * [Amazon RDS, Cloud Relational Database Service: MySQL, Oracle, SQL Server]( http://goo.gl/pfAY )
 * [Amazon Route 53]( http://aws.amazon.com/ko/route53/ )
 * [Amazon Elastic MapReduce(Amazon EMR)]( http://aws.amazon.com/ko/elasticmapreduce/ )
 * [Amazon CloudWatch]( http://goo.gl/VFe9q )
 * [Amazon Simple Email Service (Amazon SES)]( http://goo.gl/SWFLo )
* [nginx]( http://goo.gl/Y2EY ): HTTP and reverse proxy server, as well as a mail proxy server
* [Werkzeug]( http://goo.gl/SkMo ): WSGI utility library for Python.
* [unbit/uwsgi · GitHub]( http://goo.gl/vgKCW ): uWSGI application server container
* [dotCloud]( http://goo.gl/aXQg3 ): Deploy, manage and scale any web app.
* [Gunicorn]( http://goo.gl/nl93V ): Python WSGI HTTP Server for UNIX.
* [geeknam/python-gcm · GitHub]( http://goo.gl/Y0jvC ): Python client for Google Cloud Messaging for Android (GCM).
* [pylons]( http://www.pylonsproject.org/ ): web framework to develop web application framework technology in Python. Rather than focusing on a single web framework.
* [Erlang]( http://goo.gl/m8I9 ): programming language used to build massively scalable soft real-time systems with requirements on high availability.
* [gevent]( http://goo.gl/bs0gO ): coroutine-based Python networking library that uses greenlet to provide a high-level synchronous API on top of the libevent event loop.
* [memcached]( http://goo.gl/nfS5 ): in-memory key-value store for small chunks of arbitrary data (strings, objects).
* [RabbitMQ]( http://goo.gl/tkTD ): Robust messaging for applications.
* [Celery]( http://goo.gl/wRppb ): asynchronous task queue/job queue based on distributed message passing.
* [Flask]( http://goo.gl/NX50 ): microframework for Python based on Werkzeug.
* [HBase]( http://goo.gl/2kbIQ ): Hadoop database, a distributed, scalable, big data store.
* [Varnish]( http://goo.gl/YmASf ): caching HTTP reverse proxy.
* [HAProxy]( http://goo.gl/Wdab ): High Performance TCP/HTTP Load Balancer.
* [gearman]( http://goo.gl/qxQb ): job queue system, is used for long running fire and forget type work.
* [Kafka]( http://goo.gl/RKtf1 ): distributed publish-subscribe messaging system
* [robey/kestrel · GitHub]( http://goo.gl/oGVkK ): simple, distributed message queue system.
* [twitter/finagle · GitHub]( http://goo.gl/uglWO ): fault tolerant, protocol-agnostic RPC system.
* [Thrift]( http://goo.gl/S5xmY ): scalable cross-language services development, combines a software stack with a code generation engine to build services that work efficiently and seamlessly between C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, OCaml and Delphi and other languages.
* [defunkt/starling · GitHub]( http://goo.gl/Hqeko ): light weight server for reliable distributed message passing
* [tornado]( http://www.tornadoweb.org/en/stable/ ): Python web framework and asynchronous networking library.
* [Func]( http://goo.gl/DvbL2 ): secure, scriptable remote control framework.
* [evan/mongrel · GitHub]( http://goo.gl/ogrDU ): small fast HTTP library and server that runs Rails, Camping, Nitro and Iowa apps.
* [paste]( http://pythonpaste.org/ ): set of utilities for web development in Python. Paste has been described as "a framework for web frameworks". the package contains Python modules that help in implementing WSGI middleware.
* [jetty]( http://www.eclipse.org/jetty/ ): Web server and javax.servlet container, plus support for SPDY, Web Sockets, OSGi, JMX, JNDI, JASPI, AJP and many other integrations.
* [pyapns]( https://github.com/samuraisam/pyapns ): universal Apple Push Notification Service (APNS) provider.
* [node2dm]( https://github.com/Instagram/node2dm ): sending push notifications to Google's C2DM push notification server.
* [Groovy]( http://goo.gl/uvy0 ): dynamic language
for the Java platform
* [Grails]( http://goo.gl/KrxB ): full stack, web application framework for the JVM
* [99designs/ergo]( http://goo.gl/wQ3Qm ):  lightweight php5 library for request/response routing, controllers and http interaction
* [beanstalkd]( http://goo.gl/Pd4IO ): simple, fast work queue, [PHP client for beanstalkd queue]( http://goo.gl/Zc08w )
* [Unicorn]( http://goo.gl/3GOWH ): Rack HTTP server for fast clients and Unix
 * [alphagov/unicornherder]( http://goo.gl/9DUKL ): Unicorn Herder: manage daemonized (g)unicorns
* [Sinatra]( http://goo.gl/kZW6 ): DSL for quickly creating web applications in Ruby with minimal effort
* [GAE, Google App Engine]( http://goo.gl/qvc8h ): Lets you run web applications on Google's infrastructure. App Engine applications are easy to build, easy to maintain, and easy to scale as your traffic and data storage needs grow. With App Engine, there are no servers to maintain
* [SKYSCAPE]( http://goo.gl/mFYyv ): The service provider of choice for Assured Cloud Services
* [Jekyll]( http://goo.gl/0bTNg ): Simple, blog-aware, static sites.
* [Heroku]( http://goo.gl/qRH0S ): cloud application platform.
* [Clojure]( http://goo.gl/94Cv ):  dynamic programming language that targets the Java Virtual Machine.
* [JGroups]( http://goo.gl/tul6t ): toolkit for reliable messaging.
* [PHP-FPM]( http://goo.gl/Ck0n ): alternative PHP FastCGI.
* [Symfony]( http://goo.gl/wrsdi ): High Performance PHP Framework.

## DATABASE, STORAGE, DATA-MINING

* [PostgreSQL]( http://goo.gl/0PKR ): most advanced open source database.
* [repmgr]( http://www.repmgr.org/ ): open source tools that helps DBAs and System administrators manage a cluster of PostgreSQL databases.
* [pgpool Wiki]( http://goo.gl/g1aeF ): middleware that works between PostgreSQL servers and a PostgreSQL database client.
* [PgBouncer]( http://wiki.postgresql.org/wiki/PgBouncer ): lightweight connection pooler for PostgreSQL.
* [SQLAlchemy]( http://goo.gl/SLyrf ): Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.
* [South]( http://goo.gl/GPu10 ): intelligent schema and data migrations for ​Django projects.
* [twitter/gizzard · GitHub]( http://goo.gl/pKHtv ): flexible sharding framework for creating eventually-consistent distributed datastores
* [cassandra]( http://cassandra.apache.org/ ): used for high velocity writes, and lower velocity reads
* [hadoop]( http://hadoop.apache.org/ ): process unstructured and large datasets, hundreds of billions of rows.
* [vertica]( https://github.com/vertica ): used for analytics and large aggregations and joins so they don't have to write MapReduce jobs. (twitter)
* [mrjob]( https://github.com/Yelp/mrjob ): Run MapReduce jobs on Hadoop or Amazon Web Services
* [Apache Lucene - Welcome to Apache Lucene]( http://goo.gl/p4i8J )
 * [Apache Solr]( http://lucene.apache.org/solr/ ): popular, blazing fast open source enterprise search platform from the Apache LuceneTM project
* [fatcache]( https://github.com/twitter/fatcache ): Memcache on SSD.
* [google-cloud-storage]( https://cloud.google.com/products/cloud-storage ): Store, access and manage your data on Google’s storage infrastructure. Take advantage of the scale and efficiency we have built over the years.
* [haystack]( http://goo.gl/zvAmc ): Facebook photo Infrastructure.
* [Netflix/EVCache]( http://goo.gl/gcWWr ): distributed in-memory data store for the cloud.
* [Elasticsearch]( http://goo.gl/gaWlC ): Open Source Distributed Real Time Search & Analytics
* [SQL-Server]( http://goo.gl/mY9AW ): Microsoft SQL Server.
* [Doctrine]( http://goo.gl/oIqU6 ): PHP libraries primarily focused on providing persistence services

## DEPLOY, MONITORING, UTILITIES

* [Fabric]( http://goo.gl/mZ6Fu ): library and command-line tool for streamlining the use of SSH for application deployment or systems administration tasks.
* [boto/boto · GitHub]( http://goo.gl/K86QC ): python interface to aws
* [capistrano/capistrano · GitHub]( http://goo.gl/WuV8m ): Remote multi-server automation tool.
* [puppetlabs/puppet · GitHub]( http://goo.gl/wIaLd ): Server automation framework and application.
* [Exceptional]( http://goo.gl/rzaeE ): Exceptional tracks errors in web apps. It reports them in real-time.and gathers the info you need to fix them fast.
* [jzempel/flask-exceptional · GitHub]( http://goo.gl/FyWRt ): Exceptional extension for Flask.
* [rsync]( http://goo.gl/6z2Xm ): utility that provides fast incremental file transfer.
* [Nagios]( http://goo.gl/D4px ): The Industry Standard in IT Infrastructure Monitoring
* [Munin]( http://goo.gl/Oj4R ): networked resource monitoring tool that can help analyze resource trends
* [AWStats]( http://goo.gl/RMDp ): powerful and featureful tool that generates advanced web, streaming, ftp or mail server statistics, graphically
* [pingdom]( https://www.pingdom.com/ ): Website monitoring. Monitor your server and network uptime and performance for free.
* [sentry]( https://github.com/getsentry/sentry ): realtime error logging and aggregation platform
* [pagerduty]( http://www.pagerduty.com/ ): SaaS IT on-call schedule management, alerting and incident tracking.
* [scribe]( https://github.com/facebook/scribe ): server for aggregating log data that's streamed in realtime from clients. It is designed to be scalable and reliable
* [Sphinx]( http://goo.gl/DdC4N ): tool that makes it easy to create intelligent and beautiful
* [pHash.org]( http://goo.gl/DNIy0 ): perceptual hash library
* [dahlia/wand · GitHub]( http://goo.gl/wcdEe ): The ctypes-based simple ImageMagick binding for Python.
* [py-bcrypt]( http://goo.gl/UV7IZ ): strong password hashing for Python.
* [mdadm](http://linux.die.net/man/8/mdadm): manage MD devices aka Linux Software RAID.
* [twitter/snowflake · GitHub]( http://goo.gl/D3FkW ): network service for generating unique ID numbers at high scale with some simple guarantees
* [node-readability]( https://github.com/arrix/node-readability ): Server side readability with node.js
* [Netflix/asgard]( http://goo.gl/dc6k4 ): Web interface for application deployments and cloud management in Amazon Web Services (AWS)
* [Netflix/Priam]( http://goo.gl/RAccP ): Co-Process for backup/recovery, Token Management, and Centralized Configuration management for Cassandra.
* [Netflix/zuul]( http://goo.gl/p6Btb ): edge service that provides dynamic routing, monitoring, resiliency, security, and more.
* [Cacti®]( http://goo.gl/VFre ): The Complete RRDTool-based Graphing Solution.
* [LFTP]( http://goo.gl/YjIh ): sophisticated file transfer program.
* [lqez/npk]( http://goo.gl/y8uMf ): neat package system.
* [etsy/statsd]( http://goo.gl/3hYAF ): Simple daemon for easy stats aggregation.
* [new-relic]( http://goo.gl/aw4xc ): Application Performance Management & Monitoring.
* [Upstart - Wikipedia, the free encyclopedia]( http://goo.gl/wKrC1 )
* [MapIt]( http://goo.gl/6cxth ): map postcodes and geographical points to administrative areas
* [logstash]( http://goo.gl/PxCDV ): open source log management.
* [Ganglia]( http://goo.gl/N2Wu7 ): scalable distributed monitoring system for high-performance computing systems such as clusters and Grid.
* [Jenkins]( http://goo.gl/nZNOf ): extendable open source continuous integration server.
* [Graphite]( http://goo.gl/obu2 ): Scalable Realtime Graphing.
* [Google-Analytics]( http://goo.gl/ktRQ ): Web Analytics & Reporting.
* [dyn]( http://goo.gl/u6HXK ): Managed DNS | Email Delivery | SMTP | Domain Registration
* [FontForge]( http://goo.gl/WsYzE ): outline font editor.
* [DTL FontTools]( http://goo.gl/PwF8F ): Dutch Type Library.
* [Zendesk.com]( http://goo.gl/B8nc ): Customer Service Software.
