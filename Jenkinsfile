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
          curl http://localhost:3000/posts/1
            """
        }
      }
    }

    
  }
}
