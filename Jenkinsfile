pipeline {

    agent { label 'mac' }

    environment {
        workspace = pwd()
        branch = 'development'
        url = 'https://github.com/Mougly64/FastLanePractices.git'
    }

    stages {
        stage('Checkout git') {
            steps {
                git branch: branch, credentialsId: 'fastlanePruebas', url: url
            }
        }

        //https://medium.com/multinetinventiv/ci-cd-with-jenkins-docker-and-fastlane-p2-jenkins-and-docker-45960d1958fd
        stage('Setup Fastlane') {
            steps {
                sh 'security -v unlock-keychain -p sistemas.4321 ~/Library/Keychains/login.keychain-db'
                sh 'source $HOME/.bash_profile'
                //sh 'bundle --version'
                //sh 'ls -ll'
                //sh 'bundle update fastlane'
                sh 'bundle install'
                sh 'install fastlane'
            }
        }

        stage('Build') {
            steps {
                sh 'bundle exec fastlane tf'
            }
        }
    }
}
