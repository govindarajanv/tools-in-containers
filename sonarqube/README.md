# Sonarqube

```
docker pull --platform linux/x86_64 sonarqube:latest && docker run -it --rm --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest
```
