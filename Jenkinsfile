pipeline {
  agent any
  stages {
    stage('InitP') {
      steps {
        echo 'I am in InitP - Step2'
        call 'git fetch --all'
        call 'git checkout master'
        call 'git checkout dev1'
        call 'git merge master'
      } 
    }
  }
}
