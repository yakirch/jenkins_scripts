node('ec2_linux'){
    currentBuild.result = "SUCCESS"
    stage('Printing hello world'){
        sh 'echo "Hello World"'
    }
    #stage('Printing runnig_fail_task'){
    #    sh 'ech "runnig_tests"'
    #}
    stage('Printing runnig_tests'){
        sh 'echo "runnig_tests"'
    }
    stage('Printing deploy_to_production'){
        sh 'echo "deploy_to_production"'
    }
}
node{
    currentBuild.result = "SUCCESS"
    stage('Printing hello world'){
        sh 'echo "Hello World"'
    }
    stage('Printing runnig_tests'){
        sh 'echo "runnig_tests"'
    }
    stage('Printing deploy_to_production'){
        sh 'echo "deploy_to_production"'
    }
}
