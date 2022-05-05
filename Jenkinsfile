def ver
pipeline{
  agent (label 'BuildUsingSlave')
  stages{
    stage("Create Version"){
      steps{
       ver= "${env.GIT_BRANCH}-${env.BUILD_NUMBER}"
         echo "${va_r}"  
      }
    }
  }
}
