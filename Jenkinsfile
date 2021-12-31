pipeline {

    agent any

    stages {

        stage("build stage") {

            steps {

                echo "This is the build stage"
                // if you are building a java or javascript build
                // you will enter the command here for that programming\
                // language
                // sh 'npm install'
                // sh 'npm build'  

            }
        }

        stage("Test stage") {

            steps {

                echo "This a test stage of the pipeline as code"

            }

        }
        stage("Deploy stage") {

            steps {

                echo "This a deployment stage of the pipeline as code"

            }

        }


    }
}
