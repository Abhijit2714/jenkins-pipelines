@Library("shared-library") _
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                shared_library.Greet( name: "Abhijit Dhamne", comapanyname: "Infivit Technologies" )
            }
        }
    }
}
