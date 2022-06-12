pipeline {
    agent any
    tools {
      	maven 'my_maven'
    }
    stages {
        stage('compile') {
            steps {
                echo 'compile job'
            }
        }
        
        stage('build') {
            steps {
                echo 'build job'
            }
        }

        stage('test') {
            steps {
                echo 'test job'
            }
        }
    
        stage('deploy') {
            steps {
                echo 'deploy job'
            }
        }
    }
}
