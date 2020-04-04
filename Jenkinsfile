pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'curl http://localhost:5000/WeatherForecast'
            }
        }
    }
}