pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        mail(subject: 'CI start', body: 'Ci start with build', bcc: 'xpiuma@gmail.com', from: 'xpiuma@gmail.com')
      }
    }
  }
}