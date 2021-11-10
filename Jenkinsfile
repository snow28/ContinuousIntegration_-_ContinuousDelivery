pipeline {
    agent any

    stages {
        stage("release") {
             steps {
                  bat '''
                  cd ../CI-CD/builders/
                  mvn package
                  '''
             }
        }
    }
}
