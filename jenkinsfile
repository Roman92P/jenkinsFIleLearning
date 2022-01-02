pipeline{
    agent any
    stages {
            stage('Hello') {
                steps {
                    input{
                        string(name:'Test string', defaultValue='<empty>', description:'Some test string')
                    }
                }
            }
        }
}