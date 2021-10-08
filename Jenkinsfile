pipeline {
  agent node {label 'master'}
  environment {
    DOCKER_IMAGE = "quangtm199/flask-docker"
  }
  
  
    stages {
    stage("Test") {
      steps {
        sh "git clone https://github.com/xaviervasques/Jenkins.git"
    
      }
    }
  
  
  }
  
  post {
    success {
      echo "SUCCESSFUL"
    }
    failure {
      echo "FAILED"
    }
  }
  
  }