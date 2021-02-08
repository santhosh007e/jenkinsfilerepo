node {
    
      stage('git clone') 
      git 'https://github.com/santhosh007e/newrepo.git'
    }
       stage('clean') {
       sh 'mvn clean'

    }
       stage('compile') {
       sh 'mvn compile'

    }
       stage('test') {
       sh 'mvn test'

    }
       stage('package') {
       sh 'mvn package'

    }
       stage('deploy') {
       sh 'mvn deploy'    
    }
    }
