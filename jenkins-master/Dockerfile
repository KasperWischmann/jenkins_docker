FROM jenkins:2.46.2
MAINTAINER Kasper
ENV JENKINS_OPTS="--logfile=/var/log/jenkins/jenkins.log"

USER root
RUN mkdir /var/log/jenkins
RUN chown -R  jenkins:jenkins /var/log/jenkins
USER jenkins
