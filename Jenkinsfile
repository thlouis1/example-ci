pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh "npm install" 
		sh "npm install grunt-cli" 
		sh "./node_modules/grunt-cli/bin/grunt"
            }
        }
    }
    post {
        always {
           	archiveArtifacts artifacts: 'website.tgz', 
		fingerprint: true 


        }
     
    }
}
