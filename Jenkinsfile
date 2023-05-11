pipeline{
  agent any
  tools{
    maven = "maven3.8.9"
  }
  stages{
    stage(maven build){
      steps{
        sh "mvn clean package"
      }
    }
  }
}
