pipeline {
    agent any

    stages {

        stage('Output') {
            steps {
                script {
                    sh "./gradlew clean"
                    sh "./gradlew build"
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
    }
}