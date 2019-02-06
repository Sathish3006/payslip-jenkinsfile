pipeline {
    agent any 
    tools {
        maven 'Maven' 
    }
    stages {
        stage('BUILD') {
            steps {
                build 'payslip-source'
            }
        }
        stage('TEST'){
            steps{
                build 'first_test'
            }
        }
        stage('DEPLOY'){
            steps{
                build 'payslip-deploy'
            }
        }
    }
}
        
