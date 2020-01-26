pipeline {
    agent none

    stages {
        stage('Build') {
			agent any
            options {
              skipDefaultCheckOut()
            }
            steps {                
                echo 'Hello World'
            }
        }
    }
}
