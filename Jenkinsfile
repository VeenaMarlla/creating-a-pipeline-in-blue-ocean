pipeline {
  agent {
    docker {
      image 'tomcat'
      args 'replicas = 6'
    }

  }
  stages {
    stage('RunImage') {
      steps {
        sh '''echo "Hello World"

'''
      }
    }
  }
}