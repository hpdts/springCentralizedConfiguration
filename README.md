# Spring configuration Server


It reads properties from git hub https://github.com/hpdts/configSpringServer


go to http://localhost:8888/env to see configuration


# Based on 
https://spring.io/guides/gs/centralized-configuration/


# Deploy en pivotal

create manifest.yml

cf login -a https://api.run.pivotal.io

cf push APPNAME