#!/usr/bin/env groovy

pipeline {
    //Agent é o NÓ que vai rodar o job
    agent any

    //Fases do pipeline
    stages {
        
       stage('Build') {
            steps {
                script {
                    echo 'fazendo o build do projeto'
                }
            }
        }
        
       stage('Unit-test') {
            steps {
                script {
                    echo 'fazendo o test do projeto'
                }
            }
        }
        
       stage('Deploy to stage') {
            steps {
                script {
                    echo 'fazendo o deploy to stage do projeto'
                }
            }
        }
        
       stage('Acceptance do projeto') {
            steps {
                script {
                    echo 'fazendo o acceptance test do projeto'
                }
            }
        }
        
       stage('Deploy to production') {
            steps {
                script {
                    echo 'fazendo o deploy to production do projeto'
                }
            }
        }         
        
     }
}
