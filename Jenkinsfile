pipeline {
  agent any
  stages {
    stage('Master branch') {
      when {
        branch 'main'
      }
      steps {
        echo 'Working on branch master'
      }
    }
    stage('Dev branch') {
      when {
        branch 'dev'
      }
      steps {
        echo 'Working on branch dev'
      }
    }
  }
  
}
