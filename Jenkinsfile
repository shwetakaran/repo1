pipeline {
  agent any
  stages {
    stage('InitP') {
      steps {
        echo 'I am in InitP - Step2'
        sh 'git fetch --all'
        sh 'git checkout master'
        sh 'git checkout dev1'
        sh 'git merge master'
      } 
    }
  }
}
