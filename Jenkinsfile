pipeline {
   agent any

   stages {
      stage('build') {
         steps {
            snDevOpsStep()
            echo 'Hello World 3'
         }
      }
      stage('test') {
         steps {
            snDevOpsStep()
            echo 'Hello World'
         }
      }
      stage('deploy') {
         steps {
            snDevOpsStep()
            snDevOpsChange()
            echo 'Hello World'
         }
      }
   }
}
