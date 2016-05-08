<h3 align="center">
	<br>
	<img width="200" src="https://github.com/d3viant0ne/awesome-rethinkdb/blob/master/media/rethinkdb.jpg" alt="RethinkDB">
	<br>
	<br>
</h3>
## Awesome RethinkDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome RethinkDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
  - [Documentation](#documentation)
  - [Community](#community)
 - [Libraries](#libraries)
  - [JavaScript](#javascript)
  - [Python](#python)
  - [Ruby](#ruby)
  - [Java](#java)
  - [Additional Language Drivers](#additional-drivers)
 - [Research and Training](#research-and-training)
  - [Articles](#articles)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [Examples](#examples)
 - [Tools](#tools)
  - [Administration](#administration)
  - [Big Data](#big-data)
  - [Deployment](#deployment)
  - [Monitoring](#monitoring)
 - [Applications](#applications)

> <h3>RethinkDB Ecosystem</h3>

#### Documentation

- [RethinkDB](http://rethinkdb.com/docs/) - RethinkDB Documentation
- [ReQL API](http://rethinkdb.com/api/javascript/) - JavaScript ReQL command reference

#### Community

- [Request Slack Invite](http://slack.rethinkdb.com/)
- [RethinkDB StackOverflow](http://stackoverflow.com/tags/rethinkdb)
- [RethinkDB Blog](https://www.rethinkdb.com/blog/)


> <h3>Libraries</h3>

#### JavaScript
##### Drivers

- [RethinkDB JavaScript](https://www.rethinkdb.com/docs/install-drivers/javascript/) - Officially Supported JavaScript Driver.
 - Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)]( https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb) 
- [RethinkDB Dash](https://github.com/neumino/rethinkdbdash) - An advanced Node.js driver for RethinkDB with connection pool and Streams Support.
 - Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/neumino) 

##### ORM

- [Thinky](https://github.com/neumino/thinky) - JavaScript ORM for RethinkDB
 - Maintainer: `Michel`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/neumino) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/neumino) 
- [JSData RethinkDB](https://github.com/js-data/js-data-rethinkdb) - RethinkDB adapter for the js-data ORM.
 - Maintainer: `JS Data Organization`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/js-data)

##### Extension Libraries

- [RethinkDB Pool](https://github.com/hden/rethinkdb-pool) - Connection-pool for RethinkDB.
 - Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/hden) 
- [Express Session RethinkDB](https://github.com/armenfilipetyan/express-session-rethinkdb) - RethinkDB session store for Express 4.x.
 - Maintainer: `@armenfilipetyan`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/armenfilipetyan) 
 
##### Technology Integrations

- [Hapi RethinkDB CRUD](https://github.com/athlite/hapi-rethinkdb-crud) - CRUD handlers for Hapi interaction with Rethinkdb.
 - Maintainer: `Thomas Eng`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/athlite) 
- [Sails Hook Thinky](https://github.com/mwielbut/sails-hook-thinky) - A hook to enable the Thinky ORM for RethinkDB in Sails.
 - Maintainer: `Matt Wielbut`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/mwielbut) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/mwielbut) 
- [KOA RethinkDB](https://github.com/hden/koa-rethinkdb) - Koa middleware that gets you a RethinkDB client.
 - Maintainer: `Hao-kang Den`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/hden) 
- [RabbitMQ](http://rethinkdb.com/docs/rabbitmq/javascript/) - Integrating RethinkDB with RabbitMQ
 - Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)]( https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb) 

**[Back to top](#table-of-contents)**

#### Python
##### Drivers

- [RethinkDB Python](https://www.rethinkdb.com/docs/install-drivers/python/) - Officially Supported JavaScript Driver.
 - Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)]( https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb)

##### ORM

- [Remodel](https://github.com/linkyndy/remodel) - Very simple yet powerful and extensible Object Document Mapper for RethinkDB, written in Python.
 - Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
- [Rethink](https://github.com/caoimhghin/rethink) - Python RethinkDB Object Mapper Interface Inspired by Appengine NDB.
 - Maintainer: `Kevin Amerson`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/caoimhghin) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/kevinamerson)

##### Technology Integrations

- [flask-rethinkdb](https://github.com/linkyndy/flask-rethinkdb) - Adds RethinkDB support to Flask.
 - Maintainer: `Andrei Horak`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)](https://github.com/linkyndy) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/linkyndy)
- [RabbitMQ](https://www.rethinkdb.com/docs/rabbitmq/python/) - Integrating RethinkDB with RabbitMQ
 - Maintainer: `RethinkDB Team`  [![Github](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/github.png)]( https://github.com/rethinkdb) [![Twitter](https://github.com/encharm/Font-Awesome-SVG-PNG/blob/master/black/png/16/twitter.png)](https://twitter.com/rethinkdb) 

**[Back to top](#table-of-contents)**

#### Ruby
##### Drivers

##### ORM

##### Technology Integrations

**[Back to top](#table-of-contents)**

#### Java
##### Drivers

- [Java](http://rethinkdb.com/docs/install-drivers/java/) - Officially Suppported by RethinkDB.

##### ORM
##### Technology Integrations

**[Back to top](#table-of-contents)**

#### Additional Drivers

- [C#](https://github.com/bchavez/RethinkDb.Driver) - A C#/.NET RethinkDB driver striving for 100% ReQL API coverage.
- [C++](https://github.com/AtnNn/librethinkdbxx) - RethinkDB driver for C++.
- [Clojure](https://github.com/apa512/clj-rethinkdb) - A RethinkDB client for Clojure.
- [Dart](https://github.com/billysometimes/rethinkdb) - A Dart driver for RethinkDB v2.0.3.
- [Elixir](https://github.com/hamiltop/rethinkdb-elixir) - Multiplexed RethinkDB client in pure Elixir.
- [Go](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. 
- [Haskell](https://github.com/AtnNn/haskell-rethinkdb) - RethinkDB client library for Haskell.
- [Lisp](https://github.com/orthecreedence/cl-rethinkdb) - RethinkDB driver for Common Lisp.
- [Lua](https://github.com/grandquista/Lua-ReQL) - Rethinkdb driver in Lua.
- [Objective-C](https://github.com/dparnell/rethink-db-client) - A RethinkDB client written in Objective-C. 
- [Perl](https://github.com/njlg/perl-rethinkdb) - A Pure Perl RethinkDB Driver.
- [PHP](https://github.com/danielmewes/php-rql) - A PHP client driver for the RethinkDB query language (ReQL).
- [Scala](https://github.com/kclay/rethink-scala) - Scala Driver for RethinkDB.

**[Back to top](#table-of-contents)**

> <h3>>Research And Training</h3>

#### Articles

#### Talks

#### Tutorials

#### Examples

> <h3>Tools</h3>

#### Administration

#### Big Data

#### Deployment

#### Monitoring

> <h3>Applications</h3>

> <h3>License</h3>

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
