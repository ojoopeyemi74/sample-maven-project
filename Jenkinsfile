pipline {
    
   agent any
   
  stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven', mavenSettingsConfig: '') {
    sh ' mvn clean install'
}
    }
  }

}
