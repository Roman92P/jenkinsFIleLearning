pipeline{
    agent any
        stage('Input stage'){
            steps{
                echo 'Input'
                input{
                    message('Add some string')
                    parameters{
                        string(name:'String', defaultValue:'None', description:'description')
                    }
                }
            }
        }
}