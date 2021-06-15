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
                 javac LinkedList.java
                 java LinkedList
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
