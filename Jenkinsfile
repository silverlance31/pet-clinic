pipeline {
    agent any

    stages {
        stage('Code Checkout') {
            steps {
                //ws('D:\\Jenkins') {
               // sh 'make' 
                //archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true 
                echo "Checking out code"
                checkout scm
            //}
            }
        }
    }
}
