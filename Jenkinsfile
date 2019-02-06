pipeline {
    agent any 
    tools {
        maven 'Maven' 
    }
    stages {
        stage('BUILD') {
            steps {
                build 'first_build'
            }
        }
        stage('TEST'){
            steps{
                build 'first_test'
            }
        }
        stage('DEPLOY'){
            steps{
                build 'first_deploy'
            }
        }
    }
}
        
