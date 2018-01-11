# /jenkins-with-plugins

The jenkins image with suggested plugins and an account.

Prepare following files on the docker host and mount them into the directory `/run/secrets/jenkins_account` of the jenkins-with-plugins container:

- `username`
- `password`
