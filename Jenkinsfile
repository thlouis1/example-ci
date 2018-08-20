pipeline {
agent any
stages {
stage(’Build’) {
steps {
sh "npm install" 
sh "npm install grunt-cli" 
sh "./node_modules/grunt-cli/bin/grunt"
}

}
stage(’Deploy’) {
steps {
sh "echo ’Deploying....’"
}
}
}
}
