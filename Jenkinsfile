pipeline {
   agent any
   stages {
    stage('clone') {
      steps {
        script {
           git credentialsId: '9dd54130-c5cf-41cc-b4f9-cfaf8f9a94ae', url: 'https://github.com/pakeera/Task_1.git'
           ls
           git branch
           git checkout feature/0001
           echo "clone the repo .........."
          }
       }
    }
      stage ('Build') { 
                steps { 
                    echo "Building ........." 
                }
            }
  }
}
