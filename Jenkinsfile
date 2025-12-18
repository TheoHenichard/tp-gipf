node {
  stage('SCM') {
    checkout scm
  }
  stage('SonarQube Analysis') {
    withSonarQubeEnv() {
      sh "./gradlew sonar"
    }
  }
}
stages {

        stage('compileJava') {
            steps {
              
            }
        }

        stage('test') {
            steps {
                
            }
        }

        stage('sonar') {
            steps {
                 
            }
        }

        stage('jar') {
            steps {

            }
        }

    }
