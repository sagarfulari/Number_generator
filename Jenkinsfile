pipeline {
    agent any
    tools {
        maven 'Maven'
    }
    stages {
        stage("Build") {
            steps {
                sh 'mvn clean'
            }
        }
        stage ("test") {
            steps {
                echo "test stage"
            }
        }
        stage ("deploy") {
            steps {
                echo "deploy stage"
            }
        }
    }
}
