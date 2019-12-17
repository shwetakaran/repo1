pipeline {
  agent any
  stages {
    stage('InitP') {
      steps {
        echo 'I am in InitP - Step2'
        bat 'git fetch --all'
        bat 'git checkout master'
        bat 'git checkout dev1'
        bat 'git merge master'
      } 
    }
  }
}
