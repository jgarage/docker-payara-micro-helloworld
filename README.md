# docker-payara-micro-helloworld
This project contains Dockerfile to build container for a web-application that is deployed on Payara microprofile.

-For more info about Payara microstack: https://www.payara.fish/payara_micro

-The deployed web-application war-file was build from https://github.com/wildfly/quickstart/tree/master/helloworld-rs

Instructions:

-Setup a docker envirnoment (i.e. minikube)

-Build the docker image using the provided Dockerfile, ie: docker build -t hello-micro:v1 .

-Run the docker image on your environment. The Payara listens http traffic on port 8080.

-Invoke the rest api, i.e.: http://\<host\>:\<port\>/helloworld-rs/rest/xml
