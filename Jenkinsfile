pipeline {
  agent any
  stages {
        stage('Build') {
  environment {
     BRANCH_NAME = "${GIT_BRANCH.split("/")[1]}"
  }
 }
  }
}
