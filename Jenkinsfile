pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh '''git clone https://github.com/callicoder/spring-boot-websocket-chat-demo.git

cd spring-boot-websocket-chat-demo
mvn package
java -jar target/websocket-demo-0.0.1-SNAPSHOT.jar'''
      }
    }

  }
}