###centos7_build_openjdk8###
Build and compile openjdk8 src at centos7

* <code>
docker build -t bolingcavalryopenjdk:0.0.1 .
</code>
* <code>
docker run --name=jdk001 -idt bolingcavalryopenjdk:0.0.1
</code> 
* <code>
docker exec -it jdk001 /bin/bash
</code>
* <code>
cd /usr/local/openjdk
</code>
* <code>
./start_make.sh
</code>
* Waiting for the building complete, then goto build/, you will find linux-xxxxx path, new jdk is in here.
* If you have question, try send email to : zq2599@gmail.com
