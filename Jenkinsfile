pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/techmaverick89/git-workflow-team', branch: 'main')
      }
    }

    stage('Add script') {
      steps {
        sh 'echo "hello guys"'
      }
    }

  }
}