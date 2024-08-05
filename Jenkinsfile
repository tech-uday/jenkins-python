pipeline {
    agent any
    stages {
        stage('Getting Current date and time') {
            steps {
                script{
                    sh '''
                    #!/bin/bash
                    python3 dateandtime.py
     
                    ''' 
                }
            }
        }
    }
}
