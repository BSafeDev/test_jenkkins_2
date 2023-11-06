pipeline {
  agent any
  stages {
    stage('Get') {
      steps {
        git(url: 'https://github.com/BSafeDev/test_jenkkins_2', branch: 'main')
      }
    }

    stage('Create') {
      steps {
        sh '''cat "Hello World!" > HelloFile;
git add . ;'''
        git(url: 'https://github.com/BSafeDev/test_jenkkins_2', branch: 'main')
      }
    }

  }
}