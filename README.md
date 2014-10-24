docker-ruby
===========

Base container(s) for ruby developments and deployments.

Took Dockerfile from
https://registry.hub.docker.com/u/centurylink/ruby-base/ and changed
FROM container to include working UTF8 locale settings.  

## Installation

build mostalive/debian:wheezy from
https://github.com/mostalive/docker-bases and then run

```
./build.sh
```

