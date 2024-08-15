pipeline{
    agent any
    stages{
        stage ('Build and push docker image') {
         steps {
            sh './deploy.sh'
        }
      }
    }
}
