node('maven'){
    stage('checkout'){
        echo "This will clone the repo"
        git credentialsId: 'bxnyy7github', url: 'https://github.com/Titusp12/batch2.git'
    
    }
    stage('runningScript'){
        echo "This will run the Script"
        sh "sh test.sh"
    }
    stage ('Final'){
        echo " This is job is completed"
    }
    }
