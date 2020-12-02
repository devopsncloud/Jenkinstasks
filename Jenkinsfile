pipeline{
    agent{
        label "INFRA" 
    }

    environment {
        APP_VERSION = '1.0'
	SSH=credentials('SSH-CENTOS-INFRA')	

    }

    stages{
        stage("Test"){
		environment{

	APP_VERSION = '2.0'
	}
            steps{

                sh 'env'
            }


        }
    
    }


}
