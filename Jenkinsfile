pipeline {
    agent {
        label "demoAgent"
    }
    tools {
        maven 'maven'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo '2022-06-07-11:17'
                //build 'SeleniumMaven'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    post {
        always {
            echo 'job done'
            echo 'commit change!!'
        }
        
    }
}
