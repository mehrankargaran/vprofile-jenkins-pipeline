# vprofile-jenkins-pipeline

This repository contains Jenkinsfiles and notes for three CI/CD jobs for the vprofile project:
- job8-maven-build (build + sonar + upload to Nexus)
- job9-sonarqube (build + sonar + build docker + push to Docker Hub)
- job10-local-registry (build + sonar + push to local docker registry)

Replace placeholders (credentials, server IPs, tokens) with your environment values.
