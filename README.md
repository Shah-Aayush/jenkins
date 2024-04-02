# Learn Jenkins

- install jenkins through docker :
  `docker run -p 8080:8080 -p 50000:50000 -v $(pwd)/jenkins_home:/var/jenkins_home jenkins/jenkins:lts`

- go to jenkinscontainer shell :

  > `docker exec -it -u roo <container_name> sh`

- update packages :

  > `apt-get update`

- install maven :
  > `apt-get install maven`

---

## Resources

- [Pipeline Syntax](https://www.jenkins.io/doc/book/pipeline/syntax/)
- [Pipeline : Basic Steps](https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/)
