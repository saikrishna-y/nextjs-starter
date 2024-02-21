pipeline {
    agent any 
    stages { 
        stage("Build") {
            when { branch "master" }
            steps { 
               echo "I am a master branch"
            }
        }
        stage("Build main") {
            when { branch "main" }
            steps { 
               echo "I am a main branch"
            }
        }
        
    }
}
