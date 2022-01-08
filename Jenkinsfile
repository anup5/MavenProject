// Jenkinsfile
@Library('my-shared-library') _

evenOrOdd(currentBuild.getNumber())

pipeline {
	agent any
stages {
  stage('maven build') {
    steps {
      withMaven(maven: 'Maven3') {
    sh 'mvn clean install'
    }
  }

}

}
}
