// pipeline {
//
//   agent {
//     label 'ansible'
//   }
//
//   stages {
//     stage('Hello university') {
//      steps {
//        echo 'hello world'
//      }
//     }
//    stages('Hello1') {
//      steps {
//       echo 'hello hyderabad'
//      }
//    }
//
//   }
//   post {
//     always {
//        echo "sending mail"
//     }
//   }
//  }

@Library('roboshop') _

pipeline {
   agent any
   stages {
     stage('test') {
       steps {
         script {
            def abc = "hello"
            def xyz = 10

            print "abc = ${abc}"
            print "xyz = ${xyz}"

            print abc

        }
      }
    }
   }
}