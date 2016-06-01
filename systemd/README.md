docker run -it -v /var/jenkins_home --name jenkins_data busybox adduser -D -h /var/jenkins_home jenkins to add new container file

edit the volume section to read

--volumes-from=jenkins-data \
