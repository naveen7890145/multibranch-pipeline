pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1 branch') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("hotfix ") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
