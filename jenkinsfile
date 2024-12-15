pipeline {
	agent any
	stages {
		state('Hello')
			steps {
				echo "Hello from test-new Banch"
			}
		state('print_demo')
			when {
			branch "test*"
			}
			steps {
				sh "cat local.txt" 
			}
	}
}
