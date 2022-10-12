pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Sahyadri Kotipalli Learning Devops_Masterclass'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Project using Maven'
                        echo 'Build Success'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                        echo 'Deployed successfully in Staging Area'
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                        echo "Deployed successfully in Production Area"
                  }
            }
      }
}
