pipeline {
  agent any
  stages {
    stage('Server') {
      steps {
        build(job: 'DOT503', quietPeriod: 2)
      }
    }

  }
}