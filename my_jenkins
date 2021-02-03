pipeline {
        agent any
          stages{
            stage('checkout'){
              git credentialsId: 'GIT_CREDENTIALS', url: 'https://github.com/tendulkar-devops-organization/spring-boot-mongo-docker.git'
             }
             steps{
             echo "multibranch pipeline"
        }
}
