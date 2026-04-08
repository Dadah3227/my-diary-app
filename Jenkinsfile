pipeline {
    agent any
    parameters {
        string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hi'){
            steps {
                echo 'Hello there'
            }
        }
        stage('Hey'){
            steps {
                echo 'God is good'
            }
        }
        stage("HAHA"){
            steps {
                echo 'God is faithful'
            }
        }
        stage('Jesus'){
            steps {
                echo 'Pring His name'
            }
        }
        stage('Holy Ghost'){
            steps {
                echo 'Thank you HOly Ghost'
            }
        }
        stage('Hallelujah'){
            steps {
                echo 'Jesus is Lord'
            }
        }
        stage('END TIME'){
            steps {
                echo 'End of times'
            }
        }
        stage('Checkout'){
            steps {
                git branch: 'main', credentialsId: 'Githublogin', url: 'https://github.com/Dadah3227/my-diary-app.git'
                echo 'Jesus is LORD. Hallelujah'
            }
        }
        stage('The End'){
            steps {
                echo ('JESUS IS LORD')
            }
        }
    }
}
}