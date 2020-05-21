@Library('akpipeline') _

pipeline {
    
   agent any
stages {
       stage('checkout') {
         steps {
           mycodecheckout(branch: 'master', scmUrl: 'https://github.com/arunsaravana/springboot-crud-demo.git')
		 }
      }

   stage('build') {
         steps {
                mybuild()
       
                   }
        }
    }
  }
