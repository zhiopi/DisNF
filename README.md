[![Build Status](https://travis-ci.org/ab77/netflix-proxy.svg?branch=master)](https://travis-ci.org/ab77/netflix-proxy) [![Docker Pulls](https://img.shields.io/docker/pulls/ab77/sniproxy.svg?maxAge=2592000)](https://hub.docker.com/r/ab77/sniproxy/) [![Docker Stars](https://img.shields.io/docker/stars/ab77/bind.svg?maxAge=2592000)](https://hub.docker.com/r/ab77/bind/)

d18.03.0
run:
```
apt-get update\
  && apt-get -y install vim dnsutils curl sudo\
  && mkdir -p ~/netflix-proxy\
  && cd ~/netflix-proxy\
  && curl -fsSL https://github.com/zhiopi/DisNF/archive/latest.tar.gz | gunzip - | tar x --strip-components=1\
  && ./build.sh
```

`docker restart dnsmasq`. 
