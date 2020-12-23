node {
      stage('Build') {
            echo 'Pulling...' + env.BRANCH_NAME
        checkout scm

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
