pipeline {
   agent any

   stages {
      stage('build') {
         steps {
            snDevOpsStep()
            echo 'Hello World 999'
         }
      }
      stage('test') {
         steps {
            snDevOpsStep()
            echo 'Hello World 99'
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
