# ArcCTF-Test

> 部分内容参考： https://github.com/CTF-Archives/ctf-docker-template 

测试Docker文件。

使用方式：

构建Docker Image

```shell
docker build . -t arcctf-test
```

创建Docker container

```shell
docker run -p 9292:80 -e "ARC_FLAG=flag{THis_is_a_arc_flag}" -t arcctf-test
```

或者一键生成

```shell
docker compose up -d
```