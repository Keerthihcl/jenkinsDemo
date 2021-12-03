/*
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
    
}*/
// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
    // This displays colors using the 'xterm' ansi color map.
    ansiColor('xterm') {
        // Just some echoes to show the ANSI color.
        stage "\u001B[31mI'm Red\u001B[0m Now not"
    }
}
