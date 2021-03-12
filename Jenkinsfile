pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac Solution.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java Solution"""
				}
			}
		}
	}