pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        echo 'Building application'
      }
    }
    stage("Test"){
      steps{
        echo 'Testing the application'
      }
    }
    stage("Deploy"){
      steps{
        echo 'Deploying the application'
        script {
          def test = 2+2 > 3?' cool': 'not cool'
          echo test
        }
      }
    }
  }
}
