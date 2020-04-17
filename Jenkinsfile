pipeline {
	agent any
	stages{
	stage ('Checkout')
		steps{
		echo 'checkout scm'
		}
	stage ('Backup')
		steps{
		echo 'hello backup'
		}
	stage ('Build')
		steps{
	 echo 'hello demo'
		}
        stage ('Check Build')
		steps{
         echo 'hello check build'
		}
        stage ('Create Transport Form')
		steps{
         input ('create transport form?')
		}
	}
  }
