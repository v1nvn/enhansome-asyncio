> \[!WARNING]
> This project is looking for a new home. I'm no longer maintaining it.
> Please let me know if you want to take over maintainance for it.
> Write me an email to [timo@furrer.life](origin/mailto:timo@furrer.life)

# Awesome asyncio [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 435,878 | 🐛 68 | 📅 2026-01-28 with stars

> A carefully curated list of awesome Python asyncio frameworks, libraries, software and resources.

The Python [asyncio](https://docs.python.org/3/library/asyncio.html) module introduced to the standard library with Python 3.4 provides infrastructure for writing single-threaded concurrent code using coroutines, multiplexing I/O access over sockets and other resources, running network clients and servers, and other related primitives.

Asyncio is not really a brand-new technology however it appears to be very trending since a few years - especially in the Python community and with the release of Python 3.4 in March 2014.
Thus, it's pretty hard to keep yourself up-to-date with the most awesome packages out there.
Find some of those *awesome* packages here and if you are missing one we count on you to [create an Issue or a Pull Request](https://github.com/timofurrer/awesome-asyncio/blob/master/CONTRIBUTING.md) ⭐ 4,995 | 🐛 10 | 📅 2025-12-01 with your suggestion.

## Contents

* [Web Frameworks](#web-frameworks)
* [Message Queues](#message-queues)
* [Database Drivers](#database-drivers)
* [Networking](#networking)
* [GraphQL](#graphql)
* [Testing](#testing)
* [Alternative Loops](#alternative-loops)
* [Misc](#misc)
* [Writings](#writings)
* [Talks](#talks)
* [Alternatives to asyncio](#alternatives-to-asyncio)

***

## Web Frameworks

*Libraries to build web applications.*

* [FastAPI](https://github.com/tiangolo/fastapi) ⭐ 94,884 | 🐛 175 | 🌐 Python | 📅 2026-02-07 - A very high performance Python 3.6+ API framework based on type hints. Powered by Starlette and Pydantic.
* [sanic](https://github.com/channelcat/sanic) ⭐ 18,637 | 🐛 116 | 🌐 Python | 📅 2026-01-07 - Python 3.5+ web server that's written to go fast.
* [aiohttp](https://github.com/KeepSafe/aiohttp) ⭐ 16,254 | 🐛 280 | 🌐 Python | 📅 2026-02-07 - Http client/server for asyncio (PEP-3156).
* [Starlette](https://github.com/encode/starlette) ⭐ 11,901 | 🐛 53 | 🌐 Python | 📅 2026-02-01 - A lightweight ASGI framework/toolkit for building high performance services.
* [uvicorn](https://github.com/encode/uvicorn) ⭐ 10,373 | 🐛 82 | 🌐 Python | 📅 2026-02-02 - The lightning-fast ASGI server.
* [websockets](https://github.com/aaugustin/websockets/) ⭐ 5,630 | 🐛 19 | 🌐 Python | 📅 2026-01-16 - A library for building WebSocket servers and clients in Python with a focus on correctness and simplicity.
* [Quart](https://github.com/pallets/quart) ⭐ 3,591 | 🐛 66 | 🌐 Python | 📅 2025-09-01 - An asyncio web microframework with the same API as Flask.
* [autobahn](https://github.com/crossbario/autobahn-python) ⭐ 2,532 | 🐛 191 | 🌐 Python | 📅 2026-01-14 - WebSocket and WAMP supporting asyncio and Twisted, for clients and servers.
* [Django](https://www.djangoproject.com/) - An established, high-level Python web framework with a huge community and ecosystem.
* [Tornado](http://www.tornadoweb.org/en/stable/) - Performant web framework and asynchronous networking library.

## Message Queues

*Libraries to implement applications using message queues.*

* [pyzmq](https://github.com/zeromq/pyzmq) ⭐ 4,090 | 🐛 53 | 🌐 Python | 📅 2026-02-02 - Python bindings for ZeroMQ.
* [crossbar](https://github.com/crossbario/crossbar) ⭐ 2,063 | 🐛 300 | 🌐 Python | 📅 2026-01-04 - Crossbar.io is a networking platform for distributed and microservice applications.
* [aiokafka](https://github.com/aio-libs/aiokafka) ⭐ 1,362 | 🐛 185 | 🌐 Python | 📅 2026-01-31 - Client for Apache Kafka.
* [asyncio-nats](https://github.com/nats-io/asyncio-nats) ⭐ 1,182 | 🐛 198 | 🌐 Python | 📅 2026-02-05 - Client for the NATS messaging system.
* [aiozmq](https://github.com/aio-libs/aiozmq) ⭐ 431 | 🐛 31 | 🌐 Python | 📅 2022-11-10 - Alternative Asyncio integration with ZeroMQ.
* [aioamqp](https://github.com/Polyconseil/aioamqp) ⭐ 281 | 🐛 36 | 🌐 Python | 📅 2023-05-19 - AMQP implementation using asyncio.

## Database Drivers

*Libraries to connect to databases.*

* [redis-py](https://github.com/redis/redis-py) ⭐ 13,467 | 🐛 106 | 🌐 Python | 📅 2026-02-07 - Redis Python Client (which includes [aioreadis](https://github.com/aio-libs/aioredis) ⚠️ Archived now).
* [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 7,928 | 🐛 258 | 🌐 Python | 📅 2025-11-24 - Fast PostgreSQL Database Client Library for Python/asyncio.
* [Tortoise ORM](https://github.com/tortoise/tortoise-orm) ⭐ 5,476 | 🐛 502 | 🌐 Python | 📅 2026-02-07 - native multi-backend ORM with Django-like API and easy relations management.
* [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,331 | 🐛 7 | 🌐 Python | 📅 2026-02-06 - The Official MongoDB Python driver, offering both synchronous and asynchronous APIs.
* [Beanie](https://beanie-odm.dev) - An async MongoDB ODM built on [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,331 | 🐛 7 | 🌐 Python | 📅 2026-02-06 and [Pydantic](https://pydantic-docs.helpmanual.io).
* [Databases](https://github.com/encode/databases) ⚠️ Archived - Async database access for SQLAlchemy core, with support for PostgreSQL, MySQL, and SQLite.
* [GINO](https://github.com/fantix/gino) ⭐ 2,812 | 🐛 55 | 🌐 Python | 📅 2022-02-12 - is a lightweight asynchronous Python ORM based on [SQLAlchemy](https://www.sqlalchemy.org/) core, with [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 7,928 | 🐛 258 | 🌐 Python | 📅 2025-11-24 dialect.
* [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py) ⚠️ Archived - An auto-generated, fully type safe ORM powered by Pydantic and tailored specifically for your schema - supports SQLite, PostgreSQL, MySQL, MongoDB, MariaDB and more.
* [aiomysql](https://github.com/aio-libs/aiomysql) ⭐ 1,887 | 🐛 111 | 🌐 Python | 📅 2026-01-22 - Library for accessing a MySQL database
* [Piccolo](https://github.com/piccolo-orm/piccolo) ⭐ 1,854 | 🐛 60 | 🌐 Python | 📅 2026-02-06 - An ORM / query builder which can work in async and sync modes, with a nice admin GUI, and ASGI middleware.
* [aiopg](https://github.com/aio-libs/aiopg/) ⭐ 1,426 | 🐛 87 | 🌐 Python | 📅 2025-12-03 - Library for accessing a PostgreSQL database.
* [peewee-async](https://github.com/05bit/peewee-async) ⭐ 765 | 🐛 9 | 🌐 Python | 📅 2025-11-19 - ORM implementation based on [peewee](https://github.com/coleifer/peewee) ⭐ 11,927 | 🐛 0 | 🌐 Python | 📅 2026-02-07 and aiopg.
* [asyncpgsa](https://github.com/CanopyTax/asyncpgsa) ⭐ 511 | 🐛 14 | 🌐 Python | 📅 2024-02-17 - Asyncpg with sqlalchemy core support.
* [aioodbc](https://github.com/aio-libs/aioodbc) ⭐ 326 | 🐛 38 | 🌐 Python | 📅 2023-10-28 - Library for accessing a ODBC databases.
* [aioinflux](https://github.com/plugaai/aioinflux) ⚠️ Archived - InfluxDB client built on top of aiohttp.
* [aioes](https://github.com/aio-libs/aioes) ⚠️ Archived - Asyncio compatible driver for elasticsearch.
* [aiocouchdb](https://github.com/aio-libs/aiocouchdb) ⭐ 54 | 🐛 8 | 🌐 Python | 📅 2018-05-09 - CouchDB client built on top of aiohttp (asyncio).

## Networking

*Libraries to communicate in your network.*

* [httpx](https://github.com/encode/httpx) ⭐ 14,973 | 🐛 133 | 🌐 Python | 📅 2026-02-01 - asynchronous HTTP client for Python 3 with [requests](https://github.com/psf/requests) ⭐ 53,718 | 🐛 328 | 🌐 Python | 📅 2026-02-06 compatible API.
* [AsyncSSH](https://github.com/ronf/asyncssh) ⭐ 1,711 | 🐛 6 | 🌐 Python | 📅 2026-02-07 - Provides an asynchronous client and server implementation of the SSHv2 protocol.
* [aiodns](https://github.com/saghul/aiodns) ⭐ 587 | 🐛 14 | 🌐 Python | 📅 2026-02-01 - Simple DNS resolver for asyncio.
* [aioping](https://github.com/stellarbit/aioping) ⭐ 91 | 🐛 10 | 🌐 Python | 📅 2024-01-21 - Fast asyncio implementation of ICMP (ping) protocol.

## GraphQL

*Libraries to build GraphQL servers.*

* [Ariadne](https://ariadnegraphql.org) - Schema-first Python library for implementing GraphQL servers.
* [Tartiflette](https://tartiflette.io/) - Schema-first Python 3.6+ GraphQL engine built on top of `libgraphqlparser`.
* [Strawberry](https://strawberry.rocks) - Code-first Python 3 GraphQL server with Django, Flask and FastAPI/Starlette support.

## Testing

*Libraries to test asyncio based applications.*

* [pytest-asyncio](https://github.com/pytest-dev/pytest-asyncio) ⭐ 1,613 | 🐛 56 | 🌐 Python | 📅 2026-02-03 - Pytest support for asyncio.
* [aioresponses](https://github.com/pnuckowski/aioresponses) ⭐ 552 | 🐛 64 | 🌐 Python | 📅 2025-06-10 - Helper for mock/fake web requests in Python aiohttp package.
* [asynctest](https://github.com/Martiusweb/asynctest/) ⭐ 310 | 🐛 48 | 🌐 Python | 📅 2024-04-22 - Enhance the standard unittest package with features for testing. asyncio libraries
* [aresponses](https://github.com/CircleUp/aresponses) ⭐ 107 | 🐛 4 | 🌐 Python | 📅 2024-07-11 - Asyncio http mocking. Similar to the [responses](https://github.com/getsentry/responses) ⭐ 4,317 | 🐛 36 | 🌐 Python | 📅 2026-01-20 library used for [requests](https://github.com/requests/requests) ⭐ 53,718 | 🐛 328 | 🌐 Python | 📅 2026-02-06.
* [aiomock](https://github.com/nhumrich/aiomock/) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-04-19 - A python mock library that supports async methods.

## Alternative Loops

*Alternative asyncio loop implementations.*

* [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,636 | 🐛 149 | 🌐 Cython | 📅 2026-01-30 - Ultra fast implementation of asyncio event loop on top of libuv.

## Misc

*Other awesome asyncio libraries.*

* [aiofiles](https://github.com/Tinche/aiofiles/) ⭐ 3,224 | 🐛 57 | 🌐 Python | 📅 2025-10-09 - File support for asyncio.
* [ruia](https://github.com/howie6879/ruia) ⭐ 1,746 | 🐛 9 | 🌐 Python | 📅 2023-07-01 - An async web scraping micro-framework based on asyncio.
* [asgiref](https://github.com/django/asgiref) ⭐ 1,613 | 🐛 65 | 🌐 Python | 📅 2026-02-03 - Backend utils for ASGI to WSGI integration, includes sync\_to\_async and async\_to\_sync function wrappers.
* [aiocache](https://github.com/argaen/aiocache) ⭐ 1,412 | 🐛 64 | 🌐 Python | 📅 2026-02-01 - Cache manager for different backends.
* [aiorun](https://github.com/cjrh/aiorun) ⭐ 469 | 🐛 2 | 🌐 Python | 📅 2025-01-27 - A `run()` function that handles all the usual boilerplate for startup and graceful shutdown.
* [kubernetes\_asyncio](https://github.com/tomplus/kubernetes_asyncio) ⭐ 424 | 🐛 19 | 🌐 Python | 📅 2026-02-01 - Asynchronous client library for Kubernetes.
* [aiomisc](https://github.com/aiokitchen/aiomisc) ⭐ 418 | 🐛 9 | 🌐 Python | 📅 2026-01-13 - Miscellaneous utils for `asyncio`.
* [aiopath](https://github.com/alexdelorenzo/aiopath) ⭐ 193 | 🐛 24 | 🌐 Python | 📅 2026-02-05 - Asynchronous `pathlib` for asyncio.
* [aiozipkin](https://github.com/aio-libs/aiozipkin) ⭐ 192 | 🐛 23 | 🌐 Python | 📅 2026-01-19 - Distributed tracing instrumentation for asyncio with zipkin
* [aiochan](https://github.com/zh217/aiochan) ⭐ 182 | 🐛 1 | 🌐 Python | 📅 2022-11-29 - CSP-style concurrency with channels, select and multiprocessing on top of asyncio.
* [aioserial](https://github.com/changyuheng/aioserial) ⭐ 146 | 🐛 14 | 🌐 Python | 📅 2022-07-25 - A drop-in replacement of [pySerial](https://github.com/pyserial/pyserial) ⭐ 3,498 | 🐛 336 | 🌐 Python | 📅 2026-01-08.
* [async\_property](https://github.com/ryananguiano/async_property) ⭐ 98 | 🐛 9 | 🌐 Python | 📅 2023-09-05 - Python decorator for async properties.
* [aiodebug](https://github.com/qntln/aiodebug) ⭐ 65 | 🐛 0 | 📅 2022-01-04 - A tiny library for monitoring and testing asyncio programs.
* [aiosc](https://github.com/artfwo/aiosc) ⭐ 39 | 🐛 0 | 🌐 Python | 📅 2024-03-31 -  Lightweight Open Sound Control implementation.
* [taskiq](https://taskiq-python.github.io/) - Asynchronous distributed task manager (like celery, but async).

## Writings

*Documentation, blog posts, and other awesome writing about asyncio.*

* [Official asyncio documentation](https://docs.python.org/3/library/asyncio.html) - Asynchronous I/O, event loop, coroutines and tasks.
* [Short well-written intro to asyncio](https://masnun.com/python-generators-coroutines-native-coroutines-and-async-await/) - Generators, Coroutines, Native Coroutines and async/await.
* [AsyncIO for the Working Python Developer](https://hackernoon.com/asyncio-for-the-working-python-developer-5c468e6e2e8e) - A gentle introduction to asynchronous programming from basic examples working up to URL fetching.
* [Test limits of Python aiohttp](https://pawelmhm.github.io/asyncio/python/aiohttp/2016/04/22/asyncio-aiohttp.html) - Making 1 million requests with python-aiohttp.
* [ASGI (Asynchronous Server Gateway Interface)](https://asgi.readthedocs.io/en/latest/) - A spiritual successor to WSGI, intended to provide a standard interface between async-capable Python web servers, frameworks, and applications.
* [First Principles Introduction to Asyncio](https://hackernoon.com/a-simple-introduction-to-pythons-asyncio-595d9c9ecf8c) - A no-buzzword first principles introduction to the internal workings of asyncio.
* [Developing and Testing an Asynchronous API with FastAPI and Pytest](https://testdriven.io/blog/fastapi-crud/) - This tutorial looks at how to develop and test an asynchronous API with FastAPI using Test-Driven Development (TDD).
* [Python Concurrency with asyncio](https://www.manning.com/books/python-concurrency-with-asyncio) - Learn how to speed up slow Python code with concurrent programming and the cutting-edge asyncio library.

## Talks

*Recordings of awesome talks about asyncio.*

* [Topics of Interest (Python Asyncio)](https://youtu.be/ZzfHjytDceU) | [screencast](https://youtu.be/lYe8W04ERnY) | [slides](https://speakerdeck.com/dabeaz/topics-of-interest-async) - PyCon Brasil 2015 keynote (David Beazley).
* [Python Asynchronous I/O Walkthrough](https://www.youtube.com/playlist?list=PLpEcQSRWP2IjVRlTUptdD05kG-UkJynQT) - 8-part code walkthrough (Philip Guo).
* [Async/await in Python 3.5 and why it is awesome](https://www.youtube.com/watch?v=m28fiN9y_r8\&t=132s) - EuroPython 2016 (Yury Selivanov).
* [Fear and Awaiting in Async: A Savage Journey to the Heart of the Coroutine Dream](https://www.youtube.com/watch?v=E-1Y4kSsAFc) | [screencast](https://www.youtube.com/watch?v=Bm96RqNGbGo) - PyOhio 2016 keynote (David Beazley).
* [Asynchronous Python for the Complete Beginner](https://www.youtube.com/watch?v=iG6fr81xHKA) | [slides](https://speakerdeck.com/pycon2017/miguel-grinberg-asynchronous-python-for-the-complete-beginner) - PyCon 2017 (Miguel Grinberg).
* [Demystifying Python's Async and Await Keywords](https://www.youtube.com/watch?v=F19R_M4Nay4) - JetBrains TV 2020 (Michael Kennedy)

## Alternatives to asyncio

*Alternative approaches to async programming in Python, some of which attempt to support some compatibility with `asyncio`, others are not compatible at all.*

* [trio](https://github.com/python-trio/trio) ⭐ 7,157 | 🐛 316 | 🌐 Python | 📅 2026-02-01 - Pythonic async I/O for humans and snake people.
  * [trio-asyncio](https://github.com/python-trio/trio-asyncio) ⭐ 204 | 🐛 31 | 🌐 Python | 📅 2025-03-17 - re-implementation of the asyncio mainloop on top of Trio.
* [curio](https://github.com/dabeaz/curio) ⚠️ Archived - The coroutine concurrency library.
  * [Curio-Asyncio Bridge](https://github.com/dabeaz/curio/issues/190) ⚠️ Archived - basic curio -> asyncio coroutine bridge.
* [AnyIO](https://github.com/agronholm/anyio) ⭐ 2,380 | 🐛 75 | 🌐 Python | 📅 2026-02-04 - High level asynchronous concurrency and networking framework that works on top of either trio or asyncio.
