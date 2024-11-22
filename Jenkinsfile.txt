 pipeline {
    agent any
    
    stages {
        stage('Clone') {
            steps {
                echo 'Release'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project…'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Test project…'


            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy project…'

            }
        }
    }
}
