pipeline{
  agent any
  stages {
    stage ('build'){
    
      steps {
        echo 'Runnign build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  
  }

} 
