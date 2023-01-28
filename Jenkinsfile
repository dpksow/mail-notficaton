pipeline {

  agent any
  
  stages{
    stage ('Build'){
      steps{
        echo "Builing the project"
        sh 'ajbfagfiaf'
    }
  }
  }
    post{
      success{
        emailext attachLog: true, body: 'mail sent out from jenkins', subject: 'Test mail -success', to: 'deepak.sekar@cyberium.info'
      }
      failure{
        emailext attachLog: true, body: 'mail sent out from jenkins', subject: 'Test mail-failed', to: 'deepak.sekar@cyberium.info'
      }
    }
}
