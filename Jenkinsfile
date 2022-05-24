pipeline {
    agent any

    tools { nodejs "node16" }

    stages {
        stage('running script') {
            steps {
                sh 'node index.js'
            }
        }
        
    }
}