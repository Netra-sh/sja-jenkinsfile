pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh """
                git clone https://github.com/Netra-sh/sja.git
                 ls 
                 cd sja
                 ls
                 javac sample.java
                 java sample.java
                 """
            }
        }
   
    }
post {
		cleanup {
            cleanWs deleteDirs: true
              }   
}
}
