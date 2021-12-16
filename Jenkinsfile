pipeline {
   agent any
   environment{
   component_url = "https://github.com/pakeera/Task_1.git"
    git_credentials = credentials('git.repo.passward')
   }
  parameters{
  string(name: 'branch', defaultValue: 'feature/0001', description: 'enter the branch name')
   
  }
  
   stages {
    stage('clone') {
      steps {
        script {
//            git credentialsId: 'git.repo.passward', url : component_url
         git branch: "${params.branch}", credentialsId: 'git_credentials', url: component_url
           echo "clone the repo .........."
          }
       }
    }
      stage ('Build') { 
        steps{
                withMaven {
		    sh "mvn clean install"
                    echo "Build is successfull ........." 
                }
            }
      }
  }
}
