pipeline {
  agent any 

  stages {

    stage('checkout'){
      steps {
      checkout scm
      }
    }

    stage ('curl'){
      steps {
        script {
          echo'calling tool'

          sh"""
                curl http://localhost:8080/job/Devops/job/CURL
            """
        }
      }
    }

    
  }
}
