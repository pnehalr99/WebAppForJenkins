 pipeline {
  agent any 
  tools {
      maven "3.8.1"
      }
      stages {
      stages('Clean and Install') {
        steps {
          bat 'mvn clean install'
          }
          }
          stage('Package') {
          steps {
          bat 'mvn package'
          }
          }
          }
          }
