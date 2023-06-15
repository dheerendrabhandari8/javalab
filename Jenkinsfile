pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
               git branch: 'main', credentialsId: 'git_hub', url: 'https://github.com/dheerendrabhandari8/javalab.git'
            }
        }
    }
}
