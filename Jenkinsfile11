node ('s1') {
    stage('clone java project') { 
        git 'https://github.com/tusharshingote09/java.git'
    }
    stage('Build java') {
        sh '''javac Test.java
              java Test'''
    }
}
