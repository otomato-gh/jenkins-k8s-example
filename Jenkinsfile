pipeline {
    agent {
        kubernetes {
          yamlFile 'mypod.yaml'
        }                   
    }
    stages {
        stage ("one") {
            steps {
                sh "env"
            }
        }
    }
}
