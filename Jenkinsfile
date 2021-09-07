pipeline {
	agent any
	stages {
		stage('Maven Install') {
		      agent {
			docker {
			  image 'maven:3.5.0'
			}
		      }
		stage("Cleaning Stage") {
			steps {
				sh 'mvn clean install'
			}
		  }
		}
		
		
	}

