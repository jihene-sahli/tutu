pipeline {
    agent any
    stages {
       stage ('compile stage') {
          steps { withMaven (maven : 'maven-3.3.9') {
                     sh 'mvn clean package'
                     }
                }
           } 
         }  
