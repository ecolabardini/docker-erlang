## docker-erlang

[![](https://images.microbadger.com/badges/image/ecolabardini/erlang.svg)](https://microbadger.com/images/ecolabardini/erlang "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/ecolabardini/erlang.svg)](https://microbadger.com/images/ecolabardini/erlang "Get your own version badge on microbadger.com")

This is a base [Docker](http://docker.io) image for [Erlang](http://www.erlang.org/) projects.

#### What is Erlang

Erlang is a programming language used to build massively scalable soft real-time systems with requirements on high availability. Some of its uses are in telecoms, banking, e-commerce, computer telephony and instant messaging. Erlang's runtime system has built-in support for concurrency, distribution and fault tolerance.

Please see the [Erlang website](http://www.erlang.org/) or the [Erlang Quick Start](http://www.erlang.org/static/getting_started_quickly.html).

#### What is OTP

OTP is set of Erlang libraries and design principles providing middle-ware to develop these systems. It includes its own distributed database, applications to interface towards other languages, debugging and release handling tools.

Please see the [OTP Quickstart](http://www.erlang.org/doc/design_principles/users_guide.html).

## How to Use this Image

#### Run as an interactive shell

```
  $ docker run -it ecolabardini/erlang /bin/bash
  $ erl
```

#### Create a `Dockerfile` in your Project

```
  FROM ecolabardini/erlang
```

#### Issues & Contribution Info

Please contact me if you have any ideas, suggestions or, even better, you want to collaborate.

## License

Erlang is distributed under the [Erlang Public License](http://www.erlang.org/EPLICENSE).

This repository is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
