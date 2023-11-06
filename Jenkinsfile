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
        sh 'cat "Hello World!" > HelloFile'
        sh 'git add .'
      }
    }

    stage('Deploy') {
      steps {
        echo 'It\'s work'
      }
    }

  }
}