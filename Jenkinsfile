pipeline {
    agent any

    stages {
    
        stage('Terraform init') {           
            steps {
                sh 'mvn -version'
                sh 'terraform --version'
                // sh 'terraform init -input=false'
            }
        }
    
  }
}
