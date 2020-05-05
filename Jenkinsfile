pipeline {
  agent any
  stages {
  stage('Ansible Lint') {
      steps {
        script {
          sh 'ansible-lint -x 503,201 .'
        }
      }
}
}
      post{
	always{
	  deleteDir()
}
}
}
