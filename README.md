1. Build image via:  
```$ docker build -t jenkins/jenkins -f "jenkins.dockerfile" .```
2. Run container on ```8080``` port:  
```$ docker run --name jenkins-server -p 8080:8080 -p 50000:50000 jenkins/jenkins```