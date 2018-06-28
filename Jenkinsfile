pipeline {
  agent {
    docker {
      image 'tomcat'
      args '-p 8085:8085'
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