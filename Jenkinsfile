pipeline{
    agent any
    stages {
            stage('Hello') {
                steps {
                    input {
                        message "Give string input"
                        string(name: 'Test_String', defaultValue: 'None', description: 'Put some test string')                        }
                    }
                }
            }
        }
}