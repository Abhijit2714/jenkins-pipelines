@Library("shared-library") _
pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                shared_library( name: "Abhijit Dhamne", companyname: "XYZ Technologies" )
            }
        }
        // stage('Worning') {
        //     steps {
        //         script {
        //              shared_library.warning 'Do it fast!!!!'
        //         }
        //     }
        // }
    }
}
