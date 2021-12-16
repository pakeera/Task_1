 pipeline {
   agent any
   environment{
   component_url = "https://github.com/pakeera/Task_1.git"
    git_credentials = credentials('	git.repo.passward')
   }
   stages {
    stage('clone') {
      steps {
        script {
//            git credentialsId: '	git.repo.passward', url : component_url
          sh " git clone credentialsId: 'git_credentials' url: component_url "
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
