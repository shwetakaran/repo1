pipeline {
  agent any
  stages {
    stage('InitP') {
      steps {
        echo 'I am in InitP - Step2'
        git fetch --all
        git checkout master
        git checkout dev1
        git merge master
      } 
    }
  }
}
