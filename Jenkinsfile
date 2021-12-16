pipeline {
   agent any
   stages {
    stage('Checkout') {
      steps {
        script {
           git credentialsId: 'jenkins-user-github', url: 'https://github.com/pakeera/Task_1.git'
          
          }
       }
    }
  }
}
