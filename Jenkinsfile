pipeline {
    agent any
    
    stages {
    	
        stage('Java Build') {
        	steps {
        		echo "java build"
				sh"""
                    cd ./simple-project
					mvn -X clean package
                    mvn -X clean deploy
				"""
        	}
        }
    }
}