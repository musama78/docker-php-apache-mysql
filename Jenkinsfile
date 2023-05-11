pipeline {
  agent any
//   {
//     label "abc"
//   }
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'sudo docker-compose up -d'
      }
    }
  }
}
