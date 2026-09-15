pipeline {
    agent { label 'main_agent' }
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn'
            }
        }
        
    }
}
