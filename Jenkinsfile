pipeline {
	agent any
	stages {
		stage('Hello') {
			steps {
				echo "Hello from test-new Banch"
			}
		}
		stage('print_demo') {
			when {
			branch "test*"
			}
			steps {
				sh "cat local.txt"  
			}
		}
	}
}
