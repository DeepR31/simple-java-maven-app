pipeline {
  agent worker1
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean install'
            }
        } 
    }
}
