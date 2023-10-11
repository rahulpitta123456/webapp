pipeline {
    agent any

    stages {
        stage('
              tage1') {
            steps {
                echo 'git checkout'
                git 'https://github.com/sebsto/webapp.git'
            }
        }
         stage('stage2') {
             steps {
                 echo 'maven clean'
                 bat 'mvn package'
            }
        }
         stage('stage3') {
             steps {
                 echo 'maven package'  
                 bat 'mvn package'
            }
        }
    }
}
