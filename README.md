# docker-payara-micro-helloworld
Dockerized Payara-microstack helloword jax-rs example

Dockerfile and helloworld web-application to execute it on Payara microprofile

-For more info about Payara microstack: https://www.payara.fish/payara_micro

-The deployed helloworld-war was build from https://github.com/wildfly/quickstart/tree/master/helloworld-rs

Instructions:

-Setup docker envirnoment (i.e. minikube)

-Build the docker image using the provided Dockerfile, ie: docker build -t hello-micro:v1 .

-Run the docker image on your environment

-Call the rest api, i.e.: http://\<your-ip\>:\<port\>/helloworld-rs/rest/xml
