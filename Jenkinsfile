pipeline {
  agent any
//   {
//     label "abc"
//   }
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'docker-compose up -d'
      }
    }
  }
}
