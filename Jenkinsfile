def ver
pipeline{
  agent {label 'BuildUsingSlave'}
  stages{
    stage("Create Version"){
      steps{
        script{
               ver = "${env.GIT_BRANCH}-${env.BUILD_NUMBER}"
               echo "${ver}"
        }
      }
    }
  }
}
