pipeline {
    agent any
    stages {
       stage('build') {
           steps {
	        echo'build has been completed'
            sh 'python --version'
            sh 'python pipeline.py'
            sh 'cat Jenkinsfile'
	       	}
	     }
       stage ('test') {
            steps {
             sh 'ls'
             sh 'cat hello-world.py'
            }
         }
    }
}