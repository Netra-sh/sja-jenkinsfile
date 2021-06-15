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
                 javac LinkedLists.java
                 java LinkedLists
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
