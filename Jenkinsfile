pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                input {
                    message "Give string"
                    parameters{
                        string(name:'String', defaultValue:'None', description:'input string')
                    }
                }
            }
        }
    }
}
