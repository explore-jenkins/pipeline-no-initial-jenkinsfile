pipeline {
  agent {
    node {
      label 'worker_node1'
    }
    
  }
  stages {
    stage('Source') {
      steps {
        git 'http://github.com/explore-jenkins/pipeline-no-initial-jenkinsfile'
      }
    }
  }
  environment {
    USER_EMAIL = 'jenkinsuser@mypipeline.com'
  }
}