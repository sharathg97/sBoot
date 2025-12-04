pipeline {
agent any
tools {
          jdk 'java8'   
        }
stages {
  stage('compile'){
    steps {
  sh 'mvn compile'
  }
  }
  stage('test')
  { steps {
  sh 'mvn test'
  }
  }
  stage('build'){
    steps {
  sh 'mvn clean install'
}
  }
}
}
