pipeline {
    agent any

    stages {
      stage('User input') {
            input {
                message "Give some string"
                ok "Test input"
                parameters {
                    string(name: 'String', defaultValue: 'None', description: 'Test string input')
                }
            }
            steps {
                echo "Your string ${String}"
            }
        }
    }
}
