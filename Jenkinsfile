pipeline {
    agent any 
    stages { 
        stage("Build") {
            when { branch "master" }
            steps { 
               echo "I am a master branch"
            }
        }
        stage("Build") {
            when { branch "main" }
            steps { 
               echo "I am a main branch"
            }
        }
        
    }
}
