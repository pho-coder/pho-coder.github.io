---
layout:     post
title:      "filebeat发送kafka"
subtitle:   ""
date:       2017-10-02 23:23:23
author:     "phoenix"
header-img: ""
tags:
    - filebeat
    - kafka
---
> 最近发现用docker做demo特别方便，尝试做了个filebeat send kafka的Dockerfile，放在了github上，有需要的可以拿走

#### 本地build image

```shell
docker build -t filebeat-demo:v1 github.com/pho-coder/docker-filebeat-kafka
```

#### 启动demo

```shell
docker run -it filebeat-demo:v1 bash
./start.sh
```
