pipeline{
  agent any
  
  tools {
  maven 'Maven 1'
}
  stages{
    stage ("git stage"){
      steps{
      git branch: 'main', url: 'https://github.com/Mefor9/Jenkins-pipeline.git'
      }
    
    }
    stage("Build stage"){
      steps{
        sh 'mvn -version'
      }
    }
  }
  
}
