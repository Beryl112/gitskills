pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh '''cd ../
touch test.txt'''
      }
    }
    stage('') {
      steps {
        mail(subject: 'hello', body: 'hello', to: '1620801310@qq.com', from: 'beylqi@qt-asia.com', charset: 'dddd', cc: 'dddd', bcc: 'dddd', mimeType: 'ddd', replyTo: 'dddd')
      }
    }
  }
}