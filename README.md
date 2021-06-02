# Hellow
for the first repository
###Docker File template
##From: add an base image
#FROM <image>
#FROM <image>:<tag>
#FROM <image>@<digest>

##Maintainer: 
#MAINTAINER <name>
#MAINTAINER xxxx xxx <mail>

##Run:
#RUN <command>
#RUN ["executable", "param1", "param2"]
#RUN apk update

##ADD: add file into this container 
#ADD <src>...<dest>
#ADD ["<src>",..... "<dest>"]
#ADD hom* /mydir/



docker build -f /path/to/a/Dockerfile
