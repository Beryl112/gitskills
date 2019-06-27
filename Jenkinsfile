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
        mail(subject: 'hello', body: 'hello', to: '1620801310@qq.com', from: 'berylqi@qt-asia.com')
      }
    }
  }
}