pipeline {
    //agent any
    agent {
     node {
	  label 'AGENT-1'  //here 'AGENT-1' is a label name given in jenkins agent while configure.
	 }
    }  

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Test') {
            steps {
                 echo 'Testing'
            }
        }
        stage('Deploy') {
            steps {
                 echo 'Deploying'
            }
        }
    }
}