pipeline {
	agent any
	stages {
		stage('master') {
			when {
				branch 'main'
			}
			steps {
				sh 'echo "this is master"'
			}
		}
		stage('development') {
			when {
				branch 'development'
			} 
			steps {
				sh 'echo "this is development"'
			}
		}
		stage('production') {
			when {
				branch 'production'
			}
			steps {
				sh 'echo "this is production"'
			}
		}
	}
}
