pipeline{
	agent any
	stages{
		stage('compile Stage'){
			steps{
				withMaven(maven : 'maven-3'){
					bat 'mvn clean compile'
					
	
	}}
	}
	stage ('Testing Stage'){
		steps{
				withMaven(maven : 'maven-3'){
					bat 'mvn test'
	}}
	}
	
		stage ('Deployment Stage'){
		steps{
				withMaven(maven : 'maven-3'){
					bat 'mvn deploy'
	}}
	}	
}
}
