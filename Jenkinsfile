pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                git branch: 'main' , url: 'https://github.com/pritiranjan64/mavan001.git'
                sh 'mvn clean install'
          
            }
        }
    }
}
