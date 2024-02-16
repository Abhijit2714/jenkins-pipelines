@Library("shared-library") _
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                shared_library( name: "Abhijit Dhamne", comapanyname: "Infivit Technologies" )
            }
        }
        stage('Build-Address') {
            steps {
                shared_library(address: "Kamathwade" , city: "Nashik")
            }
        }
    }
}
