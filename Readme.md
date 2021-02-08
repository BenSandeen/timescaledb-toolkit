# Timescale Analytics #

This repository is the home of the Timescale Analytics team. Our mission is to
ease all things analytics when using TimescaleDB, with a particular focus on
ergonomics and performance. Our issue tracker contains more
on [the features we're planning to work on](https://github.com/timescale/timescale-analytics/labels/proposed-feature) and [the problems we're trying to solve](https://github.com/timescale/timescale-analytics/labels/feature-request),
and our [Discussions forum](https://github.com/timescale/timescale-analytics/discussions) contains ongoing conversation.

We provide a docker image containing a nightly build of the [`main`](https://github.com/timescale/timescale-analytics/tree/main)
branch of the repo, along with TimescaleDB 2.0, at
[`timescaledev/timescale-analytics:nightly`](https://hub.docker.com/r/timescaledev/timescale-.analytics/tags?page=1&ordering=last_updated).
Documentation for this version of the Timescale Analytics extension can be found
in this repository at [`extension/docs`](https://github.com/timescale/timescale-analytics/tree/main/extension/docs)

## 🖥 Try It Out ##

Run
```bash
docker run -d --name timescaledb -p 5432:5432 -e POSTGRES_PASSWORD=password timescaledev/timescale-analytics:nightly
```

## ✏️ Get Involved ##

The Timescale Analytics project is still in the initial planning stage as we
decide our priorities and what to implement first. As such, nows a great time
to help determine the direction the project will go! Have a look at the
[list of featrues we're thinking of working on](https://github.com/timescale/timescale-analytics/labels/proposed-feature) and feel free to comment on the features, expand the list, or hop on the [Discussions forum](https://github.com/timescale/timescale-analytics/discussions) for more in-depth discusssions.

## 🐯 About TimescaleDB

**[TimescaleDB](https://github.com/timescale/timescaledb)** is a
**distributed time-series database built on PostgreSQL** that scales to
over 10 million of metrics per second, supports native compression,
handles high cardinality, and offers native time-series capabilities,
such as data retention policies, continuous aggregate views,
downsampling, data gap-filling and interpolation.

TimescaleDB also supports full SQL, a variety of data types (numerics,
text, arrays, JSON, booleans), and ACID semantics. Operationally mature
capabilities include high-availability, streaming backups, upgrades over
time, roles and permissions, and security.

TimescaleDB has a **large and active user community** (tens of millions
of downloads, hundreds of thousands of active deployments, Slack channel
with thousands of members). Users include Comcast, Fujitsu,
Schneider Electric, Siemens, Walmart, Warner Music, and thousands of
others.

Developers and organizations around the world trust TimescaleDB with their
time-series data. AppDynamics (now part of Cisco Systems and one of the
largest application performance monitoring providers) relies on TimescaleDB
as its main metrics database. TimescaleDB is also the preferred (recommended)
backend datasource for Zabbix users and is natively supported in Grafana.
