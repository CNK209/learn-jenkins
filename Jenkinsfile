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
   stages('Hello1') {
     steps {
      echo 'hello hyderabad'
     }
   }

  }
  post {
    always {
       echo "sending mail"
    }
  }
 }