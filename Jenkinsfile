pipeline{
  agent any
  stages {
      stage('build'){
          steps{
          sh 'echo Hola TCS se esta descarago la app....'
          sh 'rm -rf *'
          checkout scm
          sh 'echo Compliar Maven'
          sh 'mvn complie'
          
          }
      }
      stage('Unitarias'){
          steps{
           sh 'echo Unitarias'
          
          }
      }
      stage('Frontend'){
          steps{
           sh 'echo Front'
          }
      }
  }
  
}