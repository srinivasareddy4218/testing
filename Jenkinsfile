node {
    
    stage('Build') {
             if (env.Branch_Name =~ 'main') {
                echo "main"
         stage('build')
              echo "build"
           stage('test')
                echo "test"
            } 
        else{
        if (env.Branch_Name =~ 'feature') {
                echo "feature"
            }
        }
        }
}
