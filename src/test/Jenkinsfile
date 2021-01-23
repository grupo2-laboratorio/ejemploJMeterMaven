pipeline {
	agent any
    stages {
		stage('Compile Code') {
			steps {
				dir('C:\\repositorios\\ejemploJMeterMaven'){
				bat "mvn verify -Pperformance"
				}
			}
		}
		
	}
}