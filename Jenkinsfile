pipeline {
  agent any
  stages {
    stage('InitP') {
      steps {
        echo 'I am in InitP - Step1'
      }
      steps {
        echo 'I am in InitP - Step2'
        sh 'git status'
      } 
    }

  }
}
