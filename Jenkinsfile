pipeline {

    agent

    stages {

        stage('run.sh') {

            steps {

               sh '''
                sh run.sh
                '''
            }

        }
	    stage('Hello') {

            steps {

               sh '''
                echo "Executing hello stage"
                '''
            }

        }

    }

}