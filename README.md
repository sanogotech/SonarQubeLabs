# SonarQubeLabs

- https://dzone.com/articles/how-to-analyze-your-code-quality-in-10-minutes-wit
- https://hub.docker.com/_/sonarqube

## Install via Docker

```
docker pull sonarqube
docker run -d --name sonarqube -p 9000:9000 sonarqube
```

## Unzip Sonar Scanner and Link the Sonarqube
https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/
 go to $sonarscanner_install_dir/conf/sonar-scanner.properties
 ```
 sonar.host.url=http://localhost:9000
 ```
