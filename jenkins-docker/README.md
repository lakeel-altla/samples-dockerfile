# /jenkins-docker

The jenkins image with docker for DinD (Docker in Docker).

Prepare following files on the docker host and mount them into the directory `/run/secrets/jenkins_account` of the jenkins-docker container:

- `username`
- `password`
