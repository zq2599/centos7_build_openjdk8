###centos7_build_openjdk8###
Build and compile openjdk8 src at centos7

1. <code>docker build -t bolingcavalryopenjdk:0.0.1 .</code>
2. <code>docker run --name=jdk001 -idt bolingcavalryopenjdk:0.0.1</code> 
3. <code>docker exec -it jdk001 /bin/bash</code>
4. <code>cd /usr/local/openjdk</code>
5. <code>./start_make.sh</code>
6. Waiting for the building complete, then goto build/, you will find linux-xxxxx path, new jdk is in here.
7. If you have question, try send email to : zq2599@gmail.com
