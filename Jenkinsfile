pipeline {
  agent any 
  stages {
  stage ('build') {
    steps {
      echp "Running stage with steps"
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
   }
  }
}
