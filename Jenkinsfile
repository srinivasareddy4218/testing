node {
    def getGitBranchName() {
    return scm.branches[0].name
}
    stage('Build') {
    node {
        echo 'Pulling...' + env.BRANCH_NAME
        checkout scm

    }
}
    stage('Build') {
        echo "${env.Branch_Name}"
                 if (env.Branch_Name =~ '.*main') {
                echo "main"
                 } else {
                  if (env.Branch_Name =~ '.*feature') {
                echo "feature"
            }
         }            
    }
}
