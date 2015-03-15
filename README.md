spksrc-docker
================

Docker Image providing a build environment for [SynoCommunity spksrc](https://github.com/SynoCommunity/spksrc)

Howto use
-------------

Checkout spksrc to your host edit files local and use the following docker command shell
for building packages.

```
cd /path/to/spksrc
docker pull mirweb/spksrc
docker run  -v `pwd`:/spksrc -i -t mirweb/spksrc bash
```
