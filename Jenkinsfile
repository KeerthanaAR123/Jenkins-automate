pipeline {
  agent any 
  stages {
    stage('clone') {
      git url : 'https://github.com/KeerthanaAR123/Jenkins-automate.git'
        branch:'main'
    }
  }
  stage('Run script') {
    sh 'chmod +x script.sh'
    sh './script.sh'
  }
}
}
}
