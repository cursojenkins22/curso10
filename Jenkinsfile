pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building ...'
                #git 'https://github.com/gabrielf/maven-samples.git'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing ...'
                #git 'https://github.com/gabrielf/maven-samples.git'
            }
        }
        stage('Deploy' ) {
            steps {
                echo 'Deploying ...'
                #sh "mvn clean package"
            }
        }
    }
}
