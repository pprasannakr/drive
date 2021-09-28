pipeline {
  agent any
  stages {
    parallel{
    stage('compile') {
      steps {
        build(job: 'appdeployer', propagate: true)
      }
    }
    }
  }
}
