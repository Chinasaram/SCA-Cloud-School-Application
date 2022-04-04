pipeline {
    agent any
 
    stages {
        stage('Source (Git)') {
	    steps {
              echo "pulling from github"
	    }
        }
 
        stage('Build') {
            steps {
                
                  echo "Building python script"
		    }
        }
 
 
        stage('Deploy') {
            steps {
		    sh 'cd /home/ubuntu/SCA-Cloud-School-Application/script'
                    sh 'python program.py'
            }
        }
 
 
 
 
    }
}
