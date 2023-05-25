pipeline {
  agent any
  tools {
    maven 'maven' 
  }
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
    stage ('Deploy') {
      steps {
        script {
          echo "deployed" 
        }
      }
    }
  }
}



// @Library('codeutils@master')

// def codeUtils = new org.opstree.java.javaCodePipeline()

// node{
//   codeUtils.call()
// }
