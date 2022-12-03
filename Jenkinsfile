pipeline {
  agent any
  stages {
    stage('demo_pipeline') {
      parallel {
        stage('demo_pipeline') {
          steps {
            sh '''echo \'Hello world\'
sleep 10'''
          }
        }

        stage('demo1') {
          steps {
            sh '''echo \'stage 2 hello world\'
sleep 10
'''
          }
        }

      }
    }

    stage('compile') {
      steps {
        sh '''echo \'compile stage 1\'
sleep 10'''
      }
    }

  }
  environment {
    WHO = 'MERIN'
  }
}