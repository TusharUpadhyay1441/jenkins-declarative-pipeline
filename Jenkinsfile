pipeline {
    agent any

    tools {
        // To Install the Maven version configured as "M3" and add it to the path.
        maven "mymaven"
    }

    stages {
        stage('compile') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/TusharUpadhyay1441/DevOpsClassCodes.git'

                // Run Maven on a Unix agent.
                sh "mvn compile"
            }
        }
         stage('package') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/TusharUpadhyay1441/DevOpsClassCodes.git'

                // Run Maven on a Unix agent.
                sh "mvn package"
            }
        }
    }
}
