pipeline {
agent any
stages {
stage(’Build’) {
steps {
sh "npm install" + "npm install grunt-cli" + "./node_modules/grunt-cli/bin/grunt"
  
}
}
stage(’Deploy’) {
steps {
sh "echo ’Deploying....’"
}
}
}
