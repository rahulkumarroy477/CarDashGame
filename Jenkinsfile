Pipeline{
    agent {
        docker { image 'node:16-alpine' }
    }
    stages{
        stage("Build"){
            steps{
                git branch: 'main', url: 'https://github.com/rahulkumarroy477/CarDashGame.git'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'echo "Hello world"'
            }
        }
    }
}