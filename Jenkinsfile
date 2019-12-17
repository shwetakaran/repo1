pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'stage 1 init'
        bat(script: 'bat \'echo %PATH%\'', returnStatus: true, returnStdout: true)
      }
    }

  }
  environment {
    PATH = 'C:\\WINDOWS\\SYSTEM32'
    PATH = 'C:\\Users\\nusxk41\\AppData\\Local\\Programs\\Git\\bin\\git.exe'
  }
}
