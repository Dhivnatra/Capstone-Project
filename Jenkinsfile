pipeline{
    agent any
    stages{
        stage ('Build and push image') {
         steps {
            sh './deploy.sh'
        }
      }
    }
}
