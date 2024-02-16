@Library("shared-library") _
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                shared_library( name: "Abhijit Dhamne", companyname: "Infivit Technologies" )
            }
        }
        stage('Worning') {
            steps {
                script {
                     shared_library.warning 'Do it fast!!!!'
                }
            }
        }
    }
}
