pipeline {
  agent {
    node {
      label 'normal'
    }

  }
  stages {
    stage('file') {
      steps {
        echo 'my first pipeline.'
        sh '''pwd
	ls -l /home/vagrant
echo $vaibhavathare77'''
      }
    }
  }
  environment {
    vaibhavathare77 = 'aditya2011'
  }
}
