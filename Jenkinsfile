node {
  stage('SCM'){
    echo 'Gathering code from the version control'
    git branch: '${branch}', url: 'https://github.com/APSDevp/jenkinsPipe.git'
  }
  stage('Building'){
  echo 'Building'
  releasenotes() }
  stage('Test'){
  echo 'Testing' }
  stage('Deploy'){
  echo 'Deploying' }
}
