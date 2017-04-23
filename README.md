###centos7_build_openjdk8###
Build and compile openjdk8 src at centos7

1. ```shell
docker build -t bolingcavalryopenjdk:0.0.1 .
``` 
2. ```shell
docker run --name=jdk001 -idt bolingcavalryopenjdk:0.0.1
``` 
3. ```shell
docker exec -it jdk001 /bin/bash
``` 
4. ```shell
cd /usr/local/openjdk
``` 
5. ```shell
./start_make.sh
```
6. Waiting for the building complete, then goto build/, you will find linux-xxxxx path, new jdk is in here.
7. If you have question, try send email to : zq2599@gmail.com
