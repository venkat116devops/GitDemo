pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hello gvn'
        sh 'sh "echo hello `hostname`"'
      }
    }

    stage('stage2') {
      steps {
        echo 'iam stgage2'
      }
    }

  }
}