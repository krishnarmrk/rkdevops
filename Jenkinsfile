pipeline {
agent none

stages {
   stage ('Build') {
   steps {
   echo "Hello Maven"
   sh 'mvn --version'
   }
   }

   stage ('Test') {
   steps {
   echo "Hello Java-JDK"
   sh 'java -version'
   }
   }
 }
 }