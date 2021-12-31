pipeline {

    agent any

    stages {

        stage("build stage") {

            steps {

                sh echo "This is the build stage"
                // if you are building a java or javascript build
                // you will enter the command here for that programming\
                // language
                // sh 'npm install'
                // sh 'npm build'  

            }
        }

        stage("Test stage") {

            steps {

                sh echo "This a test stage of the pipeline as code"

            }

        }
        stage("Deploy stage") {

            steps {

                sh echo "This a deployment stage of the pipeline as code"

            }

        }


    }
}
