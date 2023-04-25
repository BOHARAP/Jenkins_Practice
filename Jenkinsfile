pipeline {
    agent any

    stages {
        stage('Always') {
            
                
            steps {
                echo 'Hello World'
            }
        }
       
       stage('success') {
          
            steps {
                echo 'Hello World 1'
            }
        }
        stage('failure') {
           
            steps {
                echo 'Hello World 2'
            }
        }
    }
     post{
            always{
                echo "i will say hello always !!!!"
            }
            failure{
                echo "it failed !!!"
            }
            success{
                echo "it success!!!"
            }
        }
}
