pipeline{
  agent {
    docker {
      image 'maven3.3.3'
    }
  }

  stages{
    stage('build'){
       sh 'mvn --version'
    }
  }
}
