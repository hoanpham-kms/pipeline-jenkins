pipeline {
	agent any
	stages {
		stage('Clone') {
			steps {
				git 'https://github.com/hoanpham-kms/pipeline-jenkins.git'
			}
		}
		stage('Test output') {
			steps {
				echo 'KMS: https://github.com/hoanpham-kms/pipeline-jenkins.git'
			}
		}
	}
}
