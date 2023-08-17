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
		'''stage("git clone Stage:"){
			steps {
				git(
					url: "https://github.com/sudomando1130/test.git",
					branch: "master",
					changelog: true,
					poll: true
				)
			}
		}'''
	}
}


