pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
              echo "Building the application"
              
          }
        stage('Input') {
          steps {
            script {
      
                def resp = input message: 'Welcome All',
                  parameters: [string(defaultValue: '',
                  description: 'Enter response 1',
                  name: 'RESPONSE1'), string(defaultValue: '',
                  description: 'Enter response 2', name: 'RESPONSE2')]
                echo "${resp.RESPONSE1}"
      
    }
    echo "${resp.RESPONSE2}"
}
}
