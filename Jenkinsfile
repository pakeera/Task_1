pipeline { 
    agent any 
        stages { 
            stage('clone'){
                 steps{
                    git clone github.com/pakeera/Task_1.git
                    echo "reo got cloned"
                }
             }
            stage ('Build') { 
                steps { 
                    echo "Running build phase." 
                }
            }
        }
    }
