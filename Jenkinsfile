node('ops01Java') }{
    
      stage('VCS') {
        git 'https://github.com/shanmicheal25/GitPractice.git'
    }
    
    stage('Package') {
        sh 'mvn package'
    }
}