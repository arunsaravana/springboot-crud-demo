@Library('akpipeline') _

pipeline {
    
   agent any
stages {
       stage('checkout') {
         steps {
           mycodecheckout(branch: 'master', scmUrl: 'https://github.com/arunsaravana/spring-framework-petclinic.git')
		 }
      }

   stage('build') {
         steps {
                mybuild()
       
                   }
        }
    }
  }
