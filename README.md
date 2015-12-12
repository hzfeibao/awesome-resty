# awesome-resty

**`awesome-resty`** is a list of OpenResty / Nginx modules, Lua libraries, and related resources.

## Official Channels

* Web Site: http://openresty.org/
* Mailing List: https://groups.google.com/forum/#!forum/openresty-en ([Chinese List](https://groups.google.com/forum/#!forum/openresty))
* Github Organization: https://github.com/openresty
* Lead Developer: [@agentzh](https://github.com/agentzh)

## How to Contribute on this List?

1. [Create a New Issue](https://github.com/bungle/awesome-resty/issues/new) where you describe the needed additions, deletions or changes.
2. [Fork this repository](https://github.com/bungle/awesome-resty/fork) and make the changes, and create a pull request.
3. [Post a reply](https://groups.google.com/forum/#!topic/openresty-en/VSj4_8GNORI) in the awesome-resty thread in openresty-en mailing list.

## Contents

* [Modules](#modules)
  * [Core Modules](#core-modules)
  * [Core Nginx Modules](#core-nginx-modules)
  * [Third-party Nginx Modules](#third-party-nginx-modules)
* [Libraries](#libraries)
  * [Core Libraries](#core-libraries)
  * [Web Frameworks](#web-frameworks)
  * [Web Development Essentials](#web-development-essentials)
  * [Middleware and API Tools](#middleware-and-api-tools)
  * [Templating](#templating)
  * [Cryptography](#cryptography)
  * [Networking](#networking)
  * [Databases and Storages](#databases-and-storages)
  * [Testing and Profiling](#testing-and-profiling)
  * [Message Queuing and Task Management](#message-queuing-and-task-management)
  * [Bar Codes and QR Codes](#bar-codes-and-qr-codes)
  * [Utilities](#utilities)
  * [Date and Time](#date-and-time)
  * [Compression](#compression)
  * [Text Formats](#text-formats)
  * [Document Formats](#document-formats)
  * [Image Formats](#image-formats)
  * [Localization](#localization)
  * [Caching](#caching)
  * [Metrics and Statistics](#metrics-and-statistics)
  * [Logging](#logging)
  * [Web APIs](#web-apis)
  * [Other Sources for Libraries](#other-sources-for-libraries)
* [Books and Tutorials](#books-and-tutorials)
  * [Books](#books)
  * [Tutorials and Guides](#tutorials-and-guides)
* [Conferences, Workshops and Events](#conferences-workshops-and-events) 
* [See Also](#see-also)

## Modules

#### Core Modules

Core modules come bundled in OpenResty package.

* [ngx_openresty](https://github.com/openresty/ngx_openresty) — Turning Nginx into a full-fledged Web App Server - Sources for OpenResty Bundle Generation
* [lua-nginx-module](https://github.com/openresty/lua-nginx-module) — Embed the power of Lua into Nginx
* [echo-nginx-module](https://github.com/openresty/echo-nginx-module) — An Nginx module for bringing the power of "echo", "sleep", "time" and more to Nginx's config file
* [xss-nginx-module](https://github.com/openresty/xss-nginx-module) — Native support for cross-site scripting (XSS) in an nginx
* [set-misc-nginx-module](https://github.com/openresty/set-misc-nginx-module) — Various set_xxx directives added to nginx's rewrite module (md5/sha1, sql/json quoting, and many more)
* [encrypted-session-nginx-module](https://github.com/openresty/encrypted-session-nginx-module) — Encrypt and decrypt Nginx variable values
* [srcache-nginx-module](https://github.com/openresty/srcache-nginx-module) — Transparent subrequest-based caching layout for arbitrary nginx locations
* [lua-upstream-nginx-module](https://github.com/openresty/lua-upstream-nginx-module) — Nginx C module to expose Lua API to ngx_lua for Nginx upstreams
* [headers-more-nginx-module](https://github.com/openresty/headers-more-nginx-module) — Set and clear input and output headers...more than "add"!
* [array-var-nginx-module](https://github.com/openresty/array-var-nginx-module) — Add support for array variables to nginx config files
* [memc-nginx-module](https://github.com/openresty/memc-nginx-module) — An extended version of the standard memcached module that supports set, add, delete, and many more memcached commands
* [redis2-nginx-module](https://github.com/openresty/redis2-nginx-module) — Nginx upstream module for the Redis 2.0 protocol
* [rds-json-nginx-module](https://github.com/openresty/rds-json-nginx-module) — An nginx output filter that formats Resty DBD Streams generated by ngx_drizzle and others to JSON
* [rds-csv-nginx-module](https://github.com/openresty/rds-csv-nginx-module) — Nginx output filter module to convert Resty-DBD-Streams (RDS) to Comma-Separated Values (CSV)
* [drizzle-nginx-module](https://github.com/openresty/drizzle-nginx-module) — An Nginx upstream module that talks to mysql and drizzle by libdrizzle
* [ngx_postgres](https://github.com/FRiCKLE/ngx_postgres) — Upstream module that allows Nginx to communicate directly with PostgreSQL database
* [form-input-nginx-module](https://github.com/calio/form-input-nginx-module) — This is a nginx module that reads HTTP POST and PUT request body encoded in "application/x-www-form-urlencoded", and parse the arguments in request body into nginx variables.
* [ngx_coolkit](https://github.com/FRiCKLE/ngx_coolkit) — Collection of small and useful nginx add-ons

Please also note that there is **`resty`** command line client included in OpenResty bundle. The [command line client sources](https://github.com/openresty/resty-cli) can be found on Github.

#### Core Nginx Modules

* Please refer [Nginx Documentation](http://nginx.org/en/docs/) about the Core Nginx Modules.

#### Third-party Nginx Modules

* [ngx_pagespeed](http://ngxpagespeed.com/) ([Github](https://github.com/pagespeed/ngx_pagespeed)) — Automatic PageSpeed optimization module for Nginx
* [ModSecurity](https://www.modsecurity.org/) — Open Source Web Application Firewall
* [NAXSI](https://github.com/nbs-system/naxsi) — NAXSI is an open-source, high performance, low rules maintenance WAF for NGINX; NAXSI means Nginx Anti Xss & Sql Injection

## Libraries

#### Core Libraries

Core Libraries are bundled in OpenResty package, and you don't need to separately install them.

* [lua-resty-core](https://github.com/openresty/lua-resty-core) - New FFI-based Lua API for the ngx_lua module
* [lua-resty-upstream-healthcheck](https://github.com/openresty/lua-resty-upstream-healthcheck) — Health Checker for Nginx Upstream Servers in Pure Lua
* [lua-resty-string](https://github.com/openresty/lua-resty-string) — String utilities and common hash functions for ngx_lua and LuaJIT
* [lua-resty-lock](https://github.com/openresty/lua-resty-lock) — Simple nonblocking lock API for ngx_lua based on shared memory dictionaries
* [lua-resty-lrucache](https://github.com/openresty/lua-resty-lrucache) — Lua-land LRU Cache based on LuaJIT FFI
* [lua-resty-dns](https://github.com/openresty/lua-resty-dns) — DNS resolver for the Nginx Lua module
* [lua-resty-upload](https://github.com/openresty/lua-resty-upload) — Streaming reader and parser for HTTP file uploading based on ngx_lua cosocket
* [lua-resty-websocket](https://github.com/openresty/lua-resty-websocket) — Lua WebSocket implementation for the ngx_lua module
* [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) — Non-blocking Lua MySQL client driver for ngx_lua based on the cosocket API
* [lua-resty-memcached](https://github.com/openresty/lua-resty-memcached) — Lua memcached client driver for the ngx_lua based on the cosocket API
* [lua-resty-redis](https://github.com/openresty/lua-resty-redis) — Lua Redis client driver for the ngx_lua based on the cosocket API
* [lua-redis-parser](https://github.com/openresty/lua-redis-parser) — Redis reply parser and request constructor library for Lua
* [lua-rds-parser](https://github.com/openresty/lua-rds-parser) — Resty-DBD-Stream (RDS) parser for Lua written in C
* [lua-cjson](https://github.com/openresty/lua-cjson) — Lua cJSON is a fast JSON encoding / parsing module for Lua

#### Web Frameworks

* [Lapis](http://leafo.net/lapis/) — Lapis is a framework for building web applications using MoonScript or Lua that runs inside of a customized version of Nginx called OpenResty
* [Lusty](https://github.com/Olivine-Labs/lusty) — Lua RESTful Web Application Framework, an extensible and speedy web framework
* [GIN](https://github.com/ostinelli/gin) — A fast, low-latency, low-memory footprint, web JSON-API framework with Test Driven Development helpers and patterns
* [Quick Server](https://github.com/dualface/quickserver) — A Server Framework Based on OpenResty
* [Sailor](https://github.com/Etiene/sailor) — A Lua MVC Web Framework
* [lua-resty-rack](https://github.com/pintsized/lua-resty-rack) — A simple and extensible HTTP server framework for OpenResty
* [Vanilla](https://github.com/idevz/vanilla) — An OpenResty Web Framework
* [MOOCHINE](https://github.com/appwilldev/moochine) — A simple and lightweight web framework based on OpenResty
* [sinatra-openresty](https://github.com/jtarchie/sinatra-openresty) — Sinatra ported to OpenResty framework
* [lj-web](https://github.com/kindy/lj-web) — Lightweight Web Framework Based On ngx_openresty
* [Gimlet Cocktail](https://github.com/losinggeneration/gimlet) — A micro web application framework for OpenResty written in Moonscript inspired by Martini & Sinatra
* [durap](https://github.com/doujiang24/durap) — Durap is a Lua Web Framework based on OpenResty.
* [Ziggy Stardust](https://github.com/bakins/stardust) — Ziggy Stardust (or just "stardust") is a simple nginx/Lua framework inspired by Sinatra, Express, and Mercury
* [zLua](https://github.com/mrxx/zLua) — A Codeigniter like Lua framework based on OpenResty
* [lua-resty-stack](https://github.com/antonheryanto/lua-resty-stack) — OpenResty Simple Application Stack
* [dodolu](https://github.com/zhangf911/dodolu) — A lightweight web framework based on OpenResty
* [Octopus](https://github.com/cyberz-eu/octopus) ([Github](https://github.com/cyberz-eu/octopus)) — The Lua Web Platform

#### Web Development Essentials

* [lua-resty-cookie](https://github.com/cloudflare/lua-resty-cookie) — Lua library for HTTP cookie manipulations for OpenResty/ngx_lua
* [lua-resty-session](https://github.com/bungle/lua-resty-session) — Session library for OpenResty implementing Secure Cookie Protocol
* [lua-resty-woothee](https://github.com/toritori0318/lua-resty-woothee) — The Lua-Openresty implementation of Project Woothee, which is a multi-language user-agent strings parsers
* [router.lua](https://github.com/APItools/router.lua) — A barebones router for Lua, it matches urls and executes lua functions
* [lua-resty-mobile](https://github.com/isage/lua-resty-mobile) — This library parses HTTP headers and detects mobile device*
* [lua-resty-jwt](https://github.com/SkyLothar/lua-resty-jwt) — JWT (JSON Web Tokens) for The Great OpenResty
* [lua-resty-post](https://github.com/antonheryanto/lua-resty-post) — HTTP Post Utility for OpenResty (File Uploading Helper)
* [neturl](https://github.com/golgote/neturl) — URL and Query string parser, builder, normalizer for Lua

#### Middleware and API Tools

* [Kong](http://getkong.org/) ([GitHub](https://github.com/Mashape/kong)) — KONG: Microservice Management Layer (Secure, Manage & Extend your APIs and Microservices)

#### Templating

* [lua-resty-template](https://github.com/bungle/lua-resty-template) — A Compiling (HTML) templating engine for Lua and OpenResty
* [etlua](https://github.com/leafo/etlua) — Embedded Lua templates
* [Alternatives](https://github.com/bungle/lua-resty-template#alternatives) — Some alternative Lua templating solutions that may work just fine with OpenResty 

#### Cryptography

* [lua-resty-string](https://github.com/openresty/lua-resty-string) — String utilities and common hash functions for ngx_lua and LuaJIT
* [lua-resty-nettle](https://github.com/bungle/lua-resty-nettle) — LuaJIT FFI bindings for Nettle (a low-level cryptographic library)
* [lua-resty-murmurhash2](https://github.com/bungle/lua-resty-murmurhash2) — LuaJIT MurmurHash 2 bindings to Nginx / OpenResty murmurhash2 implementation
* [lua-resty-hmac](https://github.com/jamesmarlowe/lua-resty-hmac) — Lua driver for making and receiving hmac signed requests
* [lua-resty-scrypt](https://github.com/bungle/lua-resty-scrypt) — LuaJIT FFI-based scrypt library for OpenResty
* [lua-resty-rsa](https://github.com/doujiang24/lua-resty-rsa) — RSA functions for LuaJIT
* [lua-resty-hawk](https://github.com/golgote/lua-resty-hawk) — Hawk authentication on Nginx with Lua and OpenResty

#### Networking

* [lua-resty-http](https://github.com/pintsized/lua-resty-http) by [@pintsized](https://github.com/pintsized) — Lua HTTP client cosocket driver for OpenResty / ngx_lua
* [lua-resty-http](https://github.com/liseen/lua-resty-http) by [@liseen](https://github.com/liseen) — Lua http client driver for the ngx_lua based on the cosocket API
* [lua-resty-http](https://github.com/DorianGray/lua-resty-http) by [@DorianGray](https://github.com/DorianGray) — Lua HTTP client driver for ngx_lua based on the cosocket API
* [lua-resty-http-simple](https://github.com/bakins/lua-resty-http-simple) — Simple Lua HTTP client driver for ngx_lua
* [lua-resty-httpipe](https://github.com/timebug/lua-resty-httpipe) — Lua HTTP client cosocket driver for OpenResty / ngx_lua
* [lua-resty-httpclient](https://github.com/oneoo/lua-resty-httpclient) — Nonblocking Lua HTTP Client library for aLiLua & ngx_lua
* [lua-httpcli-resty](https://github.com/mah0x211/lua-httpcli-resty) — Lua HTTP client module for OpenResty
* [lua-resty-websocket](https://github.com/openresty/lua-resty-websocket) — Lua WebSocket implementation for the ngx_lua module
* [lua-resty-iputils](https://github.com/hamishforbes/lua-resty-iputils) — Utility functions for working with IP addresses in OpenResty
* [lua-resty-readurl](https://github.com/jamesmarlowe/lua-resty-readurl) — Lua library for capturing urls, decoding, and logging results
* [FreeWAF](https://github.com/p0pr0ck5/FreeWAF) — High-performance WAF built on the OpenResty stack
* [lua-resty-jsonrpc-batch](https://github.com/mosasiru/lua-resty-jsonrpc-batch) — JSON-RPC 2.0 Batch Request protocol module for OpenResty
* [lua-resty-limit-traffic](https://github.com/openresty/lua-resty-limit-traffic) — Lua library for limiting and controlling traffic in OpenResty/ngx_lua
* [lua-resty-limits](https://github.com/membphis/lua-resty-limits) — Limits request every second or minute
* [lua-resty-fastcgi](https://github.com/benagricola/lua-resty-fastcgi) — Lua FCGI client driver for ngx_lua based on the cosocket API
* [lua-resty-ftpclient](https://github.com/Ahsialh/lua-resty-ftpclient) —  Lua FTP client driver for the ngx_lua based on the cosocket API

#### Databases and Storages

* [lua-resty-mysql](https://github.com/openresty/lua-resty-mysql) — Non-blocking Lua MySQL client driver for ngx_lua based on the cosocket API
* [lua-resty-postgres](https://github.com/azurewang/lua-resty-postgres) — Nonblocking Lua PostgreSQL driver library for ngx_lua
* [pgmoon](https://github.com/leafo/pgmoon) — A pure Lua Postgres driver for use in OpenResy & more
* [lua-resty-memcached](https://github.com/openresty/lua-resty-memcached) — Lua memcached client driver for the ngx_lua based on the cosocket API
* [lua-resty-redis](https://github.com/openresty/lua-resty-redis) — Lua Redis client driver for the ngx_lua based on the cosocket API
* [lua-resty-redis-connector](https://github.com/pintsized/lua-resty-redis-connector) — Connection utilities for lua-resty-redis, making it easy and reliable to connect to Redis hosts, either directly or via Redis Sentinel
* [lua-resty-cassandra](https://github.com/jbochi/lua-resty-cassandra) (See also: [Mashape Fork](https://github.com/Mashape/lua-resty-cassandra)) — Pure Lua Cassandra client using CQL binary protocol
* [lua-resty-riak](https://github.com/bakins/lua-resty-riak) — Lua riak protocol buffer client driver for the ngx_lua based on the cosocket API
* [lua-resty-mongol](https://github.com/Olivine-Labs/resty-mongol/) — Native Lua Mongodb driver which supports both luasocket and ngx_lua based on the cosocket API
* [lua-resty-mongo](https://github.com/nightsailer/lua-resty-mongo) — Lua mongodb client driver for the ngx_lua based on the cosocket API
* [lua-mongo](https://github.com/boyxuper/lua-mongo) — A simple Lua Mongo driver (a fork made to work with co-sockets)
* [lua-resty-kyototycoon](https://github.com/cloudflare/lua-resty-kyototycoon) — Lua client driver for KyotoTycoon using its native wire protocol (OpenResty/ngx_lua)
* [lua-resty-tarantool](https://github.com/perusio/lua-resty-tarantool) — Library for working with Tarantool from Nginx with the embedded Lua module or with OpeRresty
* [lua-nginx-tarantool](https://github.com/ziontab/lua-nginx-tarantool) — A driver for a NoSQL database in a Lua script Tarantool build on fast nginx cosockets
* [lua-resty-ssdb](https://github.com/LazyZhu/lua-resty-ssdb) — Lua ssdb client driver for the ngx_lua based on the cosocket API, SSDB is a leveldb server
* [ledis-openresty](https://github.com/holys/ledis-openresty) — Lua LedisDB client driver for the ngx_lua based on the cosocket API
* [lua-resty-fastdfs](https://github.com/azurewang/lua-resty-fastdfs) — Nonblocking Lua FastDFS driver library for ngx_lua
* [openresty-statsd](https://github.com/lonelyplanet/openresty-statsd) — A Lua module for OpenResty to send metrics to StatsD

#### Testing and Profiling

* [Test::Nginx](http://search.cpan.org/~agent/Test-Nginx-0.24/lib/Test/Nginx.pm) — Data-driven test scaffold for Nginx C module and OpenResty Lua library development (see real-word tests in [lua-resty-redis](https://github.com/openresty/lua-resty-redis/tree/master/t))
* [nginx-systemtap-toolkit](https://github.com/openresty/nginx-systemtap-toolkit) — Real-time analyzing and diagnosing tools for Nginx based on SystemTap
* [stapxx](https://github.com/openresty/stapxx) — Simple macro language extentions to systemtap
* [FlameGraph](https://github.com/brendangregg/FlameGraph) — Flame graphs are a visualization of profiled software, allowing the most frequent code-paths to be identified quickly and accurately 
* [lua-resty-test](https://github.com/membphis/lua-resty-test) — Test frame based on OpenResty
* [busted](http://olivinelabs.com/busted/) ([Github](https://github.com/Olivine-Labs/busted)) — Elegant Lua unit testing
* [Telescope](http://telescope.luaforge.net/) ([Github](https://github.com/norman/telescope)) — Telescope is a highly customizable test library for Lua that allows for declarative tests with nested contexts

#### Message Queuing and Task Management

* [lua-resty-qless](https://github.com/pintsized/lua-resty-qless) — Lua binding to Qless (Queue / Pipeline management) for OpenResty (see also: [Qless Web Interface](https://github.com/hamishforbes/lua-resty-qless-web) implemented with OpenResty)
* [lua-resty-rabbitmqstomp](https://github.com/wingify/lua-resty-rabbitmqstomp) — Lua RabbitMQ client library which uses cosocket api for communication over STOMP 1.2 with a RabbitMQ broker which has the STOMP plugin
* [lua-resty-gearman](https://github.com/zhhchen/lua-resty-gearman) — Lua gearman client driver for the ngx_lua based on the cosocket API
* [lua-resty-kafka](https://github.com/doujiang24/lua-resty-kafka) — Lua kafka client driver for the ngx_lua based on the cosocket API
* [lua-resty-beanstalkd](https://github.com/bakins/lua-resty-beanstalkd) — Lua beanstalkd client driver for the ngx_lua based on the cosocket API
* [lua-resty-ironmq](https://github.com/bakins/lua-resty-ironmq) — Simple IronMQ client for OpenResty

#### Bar Codes and QR Codes

* [lua-resty-QRcode](https://github.com/dcshi/lua-resty-QRcode) — QR encode tool for ngx_lua
* [lua-resty-QRDecode](https://github.com/dcshi/lua-resty-QRDecode) — QR decoder for ngx_lua

#### Utilities

* [lua-resty-fileinfo](https://github.com/bungle/lua-resty-fileinfo) — LuaJIT FFI bindings to libmagic, magic number recognition library - tries to determine file types
* [lua-resty-taglib](https://github.com/bungle/lua-resty-taglib) - LuaJIT FFI bindings for TagLib - An Audio Meta-Data Library
* [lua-resty-uuid](https://github.com/bungle/lua-resty-uuid) — LuaJIT FFI bindings for libuuid, a DCE compatible Universally Unique Identifier library

#### Date and Time

These libraries are not build to using `lua-nginx-module`s date time functions (except luatz) like [`ngx.today`](https://github.com/openresty/lua-nginx-module#ngxtoday), [`ngx.time`](https://github.com/openresty/lua-nginx-module#ngxtime), [`ngx.now`](https://github.com/openresty/lua-nginx-module#ngxnow), [`ngx.localtime`](https://github.com/openresty/lua-nginx-module#ngxlocaltime), or [`ngx.utctime`](https://github.com/openresty/lua-nginx-module#ngxutctime), but they may still come handy. At some point we may need a more "official" time library for OpenResty.

* [luatz](https://github.com/daurnimator/luatz) — A Lua library for time and date manipulation (has a fallback to `ngx.now`)
* [LuaDate](https://github.com/Tieske/date) — Lua Date and Time module for Lua 5.x
* [SciLua Time Library](http://scilua.org/time.html) — Library for the manipulation of dates and periods according to the Gregorian calendar, i.e. the internationally accepted calendar for most uses

#### Compression

* [lua-resty-snappy](https://github.com/bungle/lua-resty-snappy) — LuaJIT FFI bindings for Snappy, a fast compressor/decompressor

#### Text Formats

* [lua-resty-hoedown](https://github.com/bungle/lua-resty-hoedown) — LuaJIT FFI bindings to Hoedown, a standards compliant, fast, secure markdown processing library in C
* [lua-gumbo](https://github.com/craigbarnes/lua-gumbo) — Lua bindings for the Gumbo HTML5 parsing library, with a set of DOM APIs implemented in pure Lua
* [lua-re2](https://github.com/cloudflare/lua-re2) — C and Lua wrapper for RE2 regular expression library. 
* [lua-aho-corasick](https://github.com/cloudflare/lua-aho-corasick) — C++ and Lua Implementation of the Aho-Corasick (AC) string matching algorithm 
* [lua-resty-prettycjson](https://github.com/bungle/lua-resty-prettycjson) — Lua cJSON Pretty Formatter

#### Document Formats

* [lua-resty-libxl](https://github.com/bungle/lua-resty-libxl) — LuaJIT FFI-based LibXL (Excel) library for OpenResty
* [lua-resty-hpdf](https://github.com/tavikukko/lua-resty-hpdf) — LuaJIT FFI-based libHaru (PDF) library for OpenResty

#### Image Formats

* [Lua IMagick](https://github.com/isage/lua-imagick) — Lua Pure-C Bindings to ImageMagick
* [magick](https://github.com/leafo/magick) — Lua Bindings to ImageMagick for LuaJIT using FFI
* [giflib](https://github.com/leafo/giflib) — Lua bindings to GIFLIB for LuaJIT using FFI
* [fi-luajit](https://github.com/nyfair/fi-luajit) — A LuaJIT interface to FreeImage

#### Localization

* [lua-resty-gettext](https://github.com/bungle/lua-resty-gettext) — LuaJIT FFI-based gettext library for OpenResty

#### Caching

* [lua-resty-lrucache](https://github.com/openresty/lua-resty-lrucache) — Lua-land LRU Cache based on LuaJIT FFI
* [Ledge](https://github.com/pintsized/ledge) — A Lua application for OpenResty, providing HTTP cache functionality for Nginx, using Redis as a cache / metadata store
* [lua-resty-cache](https://github.com/lloydzhou/lua-resty-cache) — HTTP Cache to Redis, can serve stale response, and using `lua-resty-lock` only allow one request to populate a new cache

#### Metrics and Statistics

* [LUAMETER](https://luameter.com/) — A Lua module for Nginx that records and provides key status and performance metrics, right from within Nginx and in real-time (Proprietary)
* [ngxtop](https://github.com/lebinh/ngxtop) — Real-Time metrics for nginx server

#### Logging

* [lua-resty-logger-socket](https://github.com/cloudflare/lua-resty-logger-socket) — Raw-socket-based Logger Library for Nginx (based on ngx_lua)
* [raven-lua](https://github.com/cloudflare/raven-lua) — A small Lua interface to Sentry
* [lua-nginx-logging](https://github.com/Lumate/lua-nginx-logging) — Logging utilities for Nginx written in Lua
* [lua-resty-logger](https://github.com/kedyyan/lua-resty-logger) — Custom Logger Library for OpenResty

#### Web APIs

* [lua-resty-github](https://github.com/jamesmarlowe/lua-resty-github) — Lua library for using the github api in the ngx_lua nginx module
* [lua-resty-hipchat](https://github.com/jamesmarlowe/lua-resty-hipchat) — Lua library for using the hipchat api
* [lua-resty-aws](https://github.com/grosskur/lua-resty-aws) — AWS signature V4 library for OpenResty + Lua
* [lua-resty-s3](https://github.com/jamesmarlowe/lua-resty-s3) — Lua driver for uploading content to Amazon S3
* [lua-resty-paypal](https://github.com/Chewbye/lua-resty-paypal) — Lua Paypal client using express checkout for OpenResty
* [lua-resty-17monip](https://github.com/timebug/lua-resty-17monip) — 17MonIP parsing library for ngx_lua
* [lua-resty-upyun](https://github.com/aCayF/lua-resty-upyun) — Upyun cloud-based platform

#### Other Sources for Libraries

* [LuaRocks / MoonRocks Repository](https://rocks.moonscript.org/) ([Search for *resty* libraries in LuaRocks](https://rocks.moonscript.org/search?q=resty&non_root=on))
* [Github Search for lua-resty-* Libraries](https://github.com/search?o=desc&q=lua-resty+in%3Aname&ref=searchresults&s=stars&type=Repositories&utf8=%E2%9C%93)
* [Lua Toolbox](https://lua-toolbox.com/)
* [luapower — Lua, JIT, batteries](http://luapower.com/)
* [List of Available LuaJIT Packages](http://wiki.luajit.org/FFI-Native-Libraries)
* [List of Available LuaJIT FFI Bindings](http://wiki.luajit.org/FFI-Bindings)

## Books and Tutorials

#### Books

* [OpenResty Best Practices](https://github.com/moonbingbing/openresty-best-practices) ([GitBook](https://www.gitbook.com/book/moonbingbing/openresty-best-practices/details)) (Chinese, use e.g. Google Translate)

#### Tutorials and Guides

* [agentzh's Nginx Tutorials](http://openresty.org/download/agentzh-nginx-tutorials-en.html)
* [Definitely an OpenResty Guide](http://www.staticshin.com/programming/definitely-an-open-resty-guide/)
* The Latest and Greatest from ngx_lua: New Features & Tools ([Summary](https://nginx.busyconf.com/activities/53d854c1c9e255cf2d00007b), [Slides](http://agentzh.org/misc/slides/nginx-conf-2014/#1), [PDF](http://agentzh.org/misc/slides/nginx-conf-2014.pdf), [Video](https://www.youtube.com/watch?v=Z0fQabvVhIk))
* [Nginx Configuration Snippets](https://github.com/lebinh/nginx-conf) — A collection of useful Nginx configuration snippets

## Conferences, Workshops and Events

* [OpenResty Con 2015, Beijing, China](http://www.iresty.com/) ([tickets](http://detail.koudaitong.com/show/goods?alias=1044ajovk&v2/goods/1044ajovk)) ([19wu.com](http://19wu.com/openrestycon2015))

## See Also

* [awesome-lua](https://github.com/LewisJEllis/awesome-lua) by [@LewisJEllis](https://github.com/LewisJEllis)
* [awesome-lua](https://github.com/forhappy/awesome-lua) by [@forhappy](https://github.com/forhappy)
* [A collection of resources covering Nginx, Nginx + Lua, OpenResty and Tengine](https://github.com/fcambus/nginx-resources)
* [Where Lua is Used](https://sites.google.com/site/marbux/home/where-lua-is-used) and [Lua Uses](http://lua-users.org/wiki/LuaUses)
