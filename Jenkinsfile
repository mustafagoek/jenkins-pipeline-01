pipeline {
    agent any
    stages {
       stage('build') {
           steps {
	       echo'build has been completed'
           sh 'python --version'
           sh 'python pipeline.py' #pipeline dosyasini calistir
	       sh 'echo Integrating pipeline using Jenkinsfile'
	       	}
	     }
    }
}