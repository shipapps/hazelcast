Hazelcast
===========

<a target="_blank" href="https://replicated.com/watch/create/init?upstream=github.com%2Fshipapps%2Fhazelcast"><img height="30" src="https://www.replicated.com/images/ship/oss/dws-green.svg" alt="Deploy with Ship"></a><br>

This ship app provides a workflow for configuring [Hazelcast IMDG](https://hazelcast.com).

### Get Started

Install [ship](https://github.com/replicatedhq/ship).

```shell
brew install ship
```

Then you can configure Hazelcast with

```shell
ship init github.com/shipapps/hazelcast
```

#### Configure using docker container

```shell
docker run -it -p 8800:8800 -v $PWD:/out \
    replicated/ship init github.com/shipapps/hazelcast
```
