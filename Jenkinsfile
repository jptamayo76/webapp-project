pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '4630d65b-533a-4b82-a9d3-2eae03cd6440', url: 'https://github.com/jptamayo76/webapp-project.git'
            }
        }
    }
}