pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''cd ../
touch test.txt'''
      }
    }
    stage('mail') {
      steps {
        mail(subject: 'dddd', body: 'ddd', from: '1620801310@qq.com', to: 'berylqi@qt-asia.com')
      }
    }
  }
}