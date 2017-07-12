FROM sonarqube:6.4-alpine

RUN cd extensions/plugins/ \
&& wget https://sonarsource.bintray.com/Distribution/sonar-java-plugin/sonar-java-plugin-4.11.0.10660.jar \
&& wget https://sonarsource.bintray.com/Distribution/sonar-scm-git-plugin/sonar-scm-git-plugin-1.2.jar \
&& wget https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/2.0.1/sonar-gitlab-plugin-2.0.1.jar
