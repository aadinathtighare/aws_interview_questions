pipeline {
    agent any
    
    
    stages {
        stage('git checkout') {
            steps {
                git 'https://github.com/aadinathtighare/end-to-end.git'
            }
        }
        stage ('maven build code') {
            steps {
                sh 'mvn clean package'
            }
    }
}
}
