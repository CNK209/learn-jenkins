pipeline {

  agent {
    label 'ansible'
  }

  stages {
    stage('Hello university') {
     steps {
       echo 'hello world'
     }
    }

  }
  post {
    always {
       echo "sending mail"
    }
  }
 }