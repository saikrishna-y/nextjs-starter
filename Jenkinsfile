pipeline {
    agent any
    stages {
        stage('first-stage'){
        when { anyOf { branch 'main'; branch 'master' } }
        steps{
          sh 'echo "iam a main branch"'
        }
      }
    }
}
