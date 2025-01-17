pipeline{
  agent any
  stages{
    stage("build"){
      steps{
        echo 'building the application.. 1'
      }
    }
    stage("test"){
      steps{
        echo 'testing the application.. 2'
        script {
            def test = 2 + 2 > 3 ? 'true' : 'false'
            echo test
        }
      }
    }
    stage("deploy"){
      steps{
        echo 'deploying the application.. 3'
      }
    }
  }
}
