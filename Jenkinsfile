pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi.., this is Anshul from LevelUp360'
                        echo 'We are Starting the Test'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploy in Staging Area"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
      }
}
