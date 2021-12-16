pipeline {
   agent any
   environment{
   component_url = "https://github.com/pakeera/Task_1.git"
   }
   stages {
    stage('clone') {
      steps {
        script {
           git credentialsId: '9dd54130-c5cf-41cc-b4f9-cfaf8f9a94ae', url : component_url
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
