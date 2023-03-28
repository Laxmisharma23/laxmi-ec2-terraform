pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "terraform init"
        sh "terraform apply -auto-approve"
      }
    }
  }

}
