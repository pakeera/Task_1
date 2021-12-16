pipeline { 
    agent any 
        stages { 
            stage('clone'){
                 steps{
                    git clone //github.com/pakeera/helloworld.git
                    echo "reop"
                }
             }
            stage ('Build') { 
                steps { 
                    echo "Running build phase." 
                }
            }
        }
    }
