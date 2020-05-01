pipeline {
  agent {
    label 'maven'
  }
  stages {
    stage("Clone Source") {
      steps {
       git 'https://github.com/Pallav695193/QuarantineDemo.git'
      }
    }
    
    stage("Mvn build"){
        steps{
            sh "mvn clean package -DskipTests"
        }
    }
  }
}
