pipeline {
    agent any
    
    triggers {
        // Polls GitHub every minute to check for new commits
        pollSCM('* * * * *') 
    }
// cscbacbdjc
    // dsjvbsjvjksv
    stages {
        stage('Build') {
            steps {
                echo 'Task: Building the code by compiling and packaging the application.'
                echo 'Tool Used: Maven (or Gradle)'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Task: Running unit tests to verify individual components and integration tests to verify combined functionality.'
                echo 'Tool Used: JUnit for Unit tests, Selenium for Integration tests'
            }
        }
        // zxcghvgh
        stage('Code Analysis') {
            steps {
                echo 'Task: Analysing code quality to ensure it meets industry standards.'
                echo 'Tool Used: SonarQube'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Task: Performing a security scan on the code to identify any vulnerabilities.'
                echo 'Tool Used: Snyk (or OWASP Dependency-Check)'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Task: Deploying the application to a staging server for pre-production testing.'
                echo 'Tool Used: AWS EC2 (or Docker)'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Task: Running integration tests on the staging environment to ensure production readiness.'
                echo 'Tool Used: Postman (or Selenium)'
            }
        }
        stage('Deploy to Production') {
            steps {
                echo 'Task: Deploying the finalized application to the production server.'
                echo 'Tool Used: AWS EC2 (or Kubernetes)'
            }
        }
    }
}
