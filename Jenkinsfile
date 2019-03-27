pipeline {
  agent any
  stages {
    stage('Project 1') {
      steps {
        bat(script: '@echo on echo This is file 01 echo ---------------- @echo off', returnStatus: true, returnStdout: true)
      }
    }
  }
}