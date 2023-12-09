pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Clean and build the Android project
                    bat "./gradlew clean assembleDebug"
                }
            }
        }

    }
}
