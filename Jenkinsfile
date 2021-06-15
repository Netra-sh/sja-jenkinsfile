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
                 javac Linkedlist.java
                 java Linkedlist
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
