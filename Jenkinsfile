pipeline
{
  agent any
  stages
  {
      stage ('clonoing code from github')
      {
          steps
          {
            git url: 'https://github.com/RavitejaAdepudi/javawar.git'
          }
      }
       stage ('building the code')
      {
          steps
          {
            sh 'touch abc'
          }
      }
      stage ('testing the code')
      {
          steps
          {
            sh 'touch bac'
          }
      }
      stage ('deploying the code')
      {
          steps
          {
           sh 'touch cab'
          }
      }
     
  }
}
