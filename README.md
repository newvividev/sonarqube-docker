# sonarqube-docker
===========================
# sonar-project.properties

# Required metadata
sonar.projectKey=
sonar.projectName=
sonar.projectVersion=1.0

# Source code location
sonar.sources=src

# SonarQube server URL
sonar.host.url=

# Authentication token (if required)
sonar.login=

==========================

# Run sonar-scanner in docker
docker run --rm   -v "$(pwd):/usr/src"   sonarsource/sonar-scanner-cli   sonar-scanner
