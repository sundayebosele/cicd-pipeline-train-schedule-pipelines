Pipeline { 
  agents any {
    stages { 
      stage {'Build'}
        steps {
          echo 'Build Automation'
          archiveArtifacts artifacts: dist/trainSchedule.zip
          sh './gradlew build --no-daemon'


}
