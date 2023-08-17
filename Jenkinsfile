pipeline{
	agent any
	stages {
		stage("Stage 1: Clean-Up"){
			steps {
				deleteDir()
			}
		}
		stage("Stage 2: Say Hello"){
			steps {
				echo "Hello this is stage number 2 :)"
			}
		}
	}
}


