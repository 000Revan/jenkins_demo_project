pipeline {
    agent any

    stages {
        stage('check out') {
            steps {
                echo 'Checking out code...'
                bat 'git clone git@github.com:000Revan/jenkins_demo_project.git'
            }
        }
    }
}
