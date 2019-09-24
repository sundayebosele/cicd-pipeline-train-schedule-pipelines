Pipeline {
  agents any {
    stages {
      stage {'Build} {
        steps {
        echo 'Running Build Automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts Artifacts: 'dist/trainSchedule.zip'

        
}
