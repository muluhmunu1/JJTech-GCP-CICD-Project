## Jjtech GCP CICD Runbook

### SonarQube Credentiala

```
Token: jjtech-cicd-java-project: ba45aeb9a0b31844cc46541f7a9219cb8d0a92c6
```

```
mvn sonar:sonar \
  -Dsonar.host.url=http://34.125.247.18:9000 \
  -Dsonar.login=ba45aeb9a0b31844cc46541f7a9219cb8d0a92c6
  ```
  ```
  username:admin
  pwd:admin
  ```

  ### Nexus Credentials
```
username:admin
pwd:admin
IP:34.125.184.227
```


### Maven Credentials
```
username:admin
pwd:admin
IP:34.125.191.179
```


### Ansible Credentials
```
username:ansible
pwd:ansible
IP:34.125.191.179
```


### Jenkins Credentials
```
username:admin
pwd:admin
IP:34.125.191.179
```


### Github Credentials
```
webhook:http://34.125.191.179:8080/github-webhook/
```