FROM docker.bintray.io/jfrog/artifactory-jcr:latest

COPY configurations/jcr/artifactory.config.import.xml /var/opt/jfrog/artifactory/var/etc/artifactory

#RUN chown -R 1030:1030 /var/opt/jfrog/artifactory/var

USER 1030