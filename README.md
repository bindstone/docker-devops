# DevOps - Docker

This is an experimental POC for trying to build a DevOps environment.

The environment itself is build by Docker and defined in the docker-compose.yaml

**Key Elements**

* GitLab https://docs.gitlab.com/omnibus/docker/

* Nexus

* Jenkins

* Sonar

Before build the docker-compose, validate to have the following folders in your repository:

* ./git_home/config

* ./git_home/logs

* ./git_home/data

* ./jenkins_home

* ./nexus_home

* ./sonar_home/conf

* ./sonar_home/data

* ./sonar_home/logs

* ./sonar_home/extensions