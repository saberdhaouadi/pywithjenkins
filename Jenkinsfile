pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
              echo "Building the application"
              sh '/usr/bin/python3 app.py'
          }
    }
}
}
