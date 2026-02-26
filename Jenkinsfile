pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git url: 'https://github.com/vermaatul2946-dotcom/jenkins-simple-demo/edit/main/Jenkinsfile.git',
            branch: 'main'
      }
    }
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}   
