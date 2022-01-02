pipeline{
    agent any
    stages {
            stage('Hello') {
                steps {
                    input{
                    message "Give input string"
                        string(name:'Test string', defaultValue='<empty>', description:'Some test string')
                    }
                }
            }
        }
}