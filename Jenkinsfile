node {
    
    stage('Build') {
        echo "${Branch_Name}"
                 if (env.Branch_Name =~ '.*main') {
                echo "main"
                 } else {
                  if (env.Branch_Name =~ '.*feature') {
                echo "feature"
            }
         }            
    }
}
