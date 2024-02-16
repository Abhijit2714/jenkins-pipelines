@Library("shared-library") _
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                shared_library( name: "Abhijit Dhamne", companyname: "Infivit Technologies" )
            }
        }
        stage('Build Address') {
            steps {
                shared_library(address: "Nashik", city: "Kamathwade")
            }
        }
    }
}
