pipeline {
    agent any

    stages {

        stage("Output") {
            steps {
                script {
                    echo "Output"
                    sh "ls"
                }
            }
        }
        stage("Build") {
            steps {
                echo "Building.."
                sh "./gradlew clean"
                sh "./gradlew build"
            }
        }
    }
}