pipeline {
  agent any

  stages {
    stage("One") {
      steps {
        echo "Hello"
      }
    }
    stage("Evaluate Master") {
      when {
        // skip this stage unless on Master branch
        branch "master"
      }
      steps {
        echo "branch master"
        echo "World"
        echo "Heal it"
      }
    }
  }
}
