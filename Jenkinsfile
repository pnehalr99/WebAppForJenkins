 pipeline {
  agent any 
  tools {
      maven "3.6.3"
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
