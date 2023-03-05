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
            env.abc = "hello"
            env.xyz = 10

            print "abc = ${abc}"
            print "xyz = ${xyz}"

            print abc

        }


        script {
          print "abc = ${abc }"
        }
      }
    }

   stage('test2') {
      steps {
        script {
          print "abc = ${abc}"
        }
      }
    }
   }
}
