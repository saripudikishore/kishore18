pipeline {
    agent { docker 'maven:3-alpine' } 
    stages {
        stage('Example Build') {
            steps {
                batch 'mvn -B clean verify'
            }
        }
    }
}