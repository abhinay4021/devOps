pipeline {
    agent {dockerfile true}
    stages{
        stage('source'){
            
        steps{
            git 'git@github.com:Venkateshharish/devOps.git'
        }
    }
    stage('Running Build'){
        environment {
                  HOME="."
                }
    steps{
        echo 'Docker file has been successfully bulit'
    }
    }
}
}