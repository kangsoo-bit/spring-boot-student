pipeline {
  agent any
  stages {
    stage('CheckOut/Git') {
      steps {
        svn(url: 'svn://122.199.232.37/svn/trunk/bitmiweb_boot', poll: true, changelog: true)
      }
    }
  }
}