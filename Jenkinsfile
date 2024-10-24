pipeline{
    agent any
    stages{
        stage("Hello"){
            steps{
                sh '''
                source myenv/bin/activate
                robot mytest.robot
                '''

            }
        }
    }
}