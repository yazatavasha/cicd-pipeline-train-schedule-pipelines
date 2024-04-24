pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'running automation'
                sh './gradlew build --no-daemon'
                archiveArtifacts: 'dist/trainSchedule.zip'
            }
        }
        stage('Test') {
            steps {
                //
            }
        }
        stage('Deploy') {
            steps {
                //
            }
        }
    }
}
