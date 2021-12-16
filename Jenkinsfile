pipeline { 
    agent any 
        stages { 
            stage('clone'){
                 steps{
                    git clone github.com/pakeera/Task_1.git
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
