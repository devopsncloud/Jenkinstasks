pipeline{
    agent{
        label "CI" 
    }


    environment {
        APP_VERSION = '1.0'
	    SSH = credentials('ci-agent	')
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
