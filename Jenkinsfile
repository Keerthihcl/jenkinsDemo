pipeline {
    agent any 
    stages {
        stage('Bulid') {
            steps {
                echo "Bulid!"
               


            }
        }
         stage('Test') {
            steps {
                echo 'Test!' 
            }
         }
          stage('Deploy') {
            steps {
                echo 'Deploy' 
            }
          }
    }
          post{
              always{
                  echo 'secuss or failure'
              }
              success{
                  echo 'success'
              }
              failure{
                  echo 'failure'
              }
          }
    
}
