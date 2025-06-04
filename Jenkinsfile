pipeline {
 agent any
 stages {
 stage('Checkout') {
 steps {
 git 'https://github.com/Harsha2318/devopslab3.git'
 }
 }
 stage('Build') {
 steps {
 sh 'mvn clean install'
 }
 }
 stage('Test') {
 steps {
 sh 'mvn test'
 }
 }
 stage('Deploy') {
 steps {
 echo 'Deploying application...'
 }
 }
 }
}
