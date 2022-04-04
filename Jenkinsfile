pipeline {
    agent any
 
    stages {
        stage('Source (Git)') {
        sh """
            cd /home/ubuntu/SCA-Cloud-School-Application/script
	    git pull
 
           """
        }
 
        stage('Build') {
            steps {
                    {
                  echo "Building python script"
              }
            }
        }
 
 
        stage('Deploy') {
            steps {
              dir('/home/ubuntu/SCA-Cloud-School-Application/script') {
                  python program.py
              }
            }
        }
 
 
 
 
    }
}
