pipeline{
  agent any
  stages {
    stage('Build'){
      echo "Build Started"
      sh './gradlew build'
      archiveArtifacts 'dist/trainSchedule.zip'

    }
  }
}
