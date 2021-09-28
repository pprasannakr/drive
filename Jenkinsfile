pipeline {
  agent any
  stages{
        stage('deploy job') {
            parallel {
              stage('compile') {
                steps {
                  build(job: 'appdeployer', propagate: true)
                }
              }
             }
            }
          }
