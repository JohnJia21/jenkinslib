@Library('jenkinslib') _

def tools = new org.devops.tools()
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                
                script {
                    def browsers = ['chrome', 'firefox']
                    for (int i = 0; i < browsers.size(); ++i) {
                        echo "Testing the ${browsers[i]} browser"

                    }
                    
                    tools.PrintMes("this is my lib!")
                }
                
            }
        }
    }
}
