pipeline {
    agent any
    stages {
        stage("Build") {
            when {
                expression {
                    // Run this stage for 'master' and 'main' branches
                    return currentBuild.branch in ['master', 'main']
                }
            }
            steps {
                echo "I am a master or main branch"
            }
        }
    }
}
