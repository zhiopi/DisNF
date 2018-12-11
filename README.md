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
