pipeline {
    agent any
    tools {
      maven 'Maven' // matches name in global tool configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package' // mvn command to package our application. This should automatically run when we run the pipeline
            }
        }
    }
}