pipeline{

  agent {  docker{ image 'maven:3.6.3' } }

  stages{
    stage('Start'){
      steps{
        echo "start"
          }
            }
    stage('Progress'){
      steps{
        echo "Progress"
          }
            }
    stage('mvn -v check'){
      steps{
        sh 'mvn --version'
        }
          }
            }
              }
