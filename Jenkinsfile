pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                git branch: 'main' , url: 'https://github.com/subhamsmile/mavan000.git'
                'sh mvn clean install'
          
            }
        }
    }
}
