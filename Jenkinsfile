pipeline {
    agent any
    
    tools { 
        maven 'Maven 3.0.5' 
        jdk 'jdk8' 
    }

    stages{
        stage('Build'){
            steps {
                sh 'mvn clean package'
            }
        }

        stage ('Deploy'){
            steps {
                echo 'Code deployed.'
            }
        }

    }
}