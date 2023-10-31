pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "M3"
    }

    stages {
        stage('Checkout') {
            steps {
                // Get some code from a GitHub repository
               git branch: "main", url:'https://github.com/ad-QA/lbg-hello-world-maven.git'

               
            }

         
        }
          stage('Build') {
            steps {
                // Get some code from a GitHub repository
               echo "now running build"
  
            }
   
        }

         stage('Compile') {
            steps {
                // Get some code from a GitHub repository
             sh "mvn clean compile"

               
            }
    }
}
}
