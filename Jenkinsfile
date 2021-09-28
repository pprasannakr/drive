pipeline {
  agent any
  stages {
    stage('compile') {
      steps {
        build(job: 'appdeployer', propagate: true)
      }
    }

  }
}