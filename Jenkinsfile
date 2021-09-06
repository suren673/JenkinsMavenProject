pipeline {
	agent any
	stages {
		stage("Cleaning Stage") {
			steps {
				sh "mvn clean"
			}
		}
		stage("Teating Stage") {
			steps {
				sh "mvn test"
			}
		}
		stage("Packaging Stage"){
			steps {
				sh "mvn package"
			}
		}
	}
}
