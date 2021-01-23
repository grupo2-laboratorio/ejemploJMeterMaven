pipeline {
	agent any
    stages {
		stage('JMeter Performance') {
			steps {
				dir('C:\\repositorios\\ejemploJMeterMaven'){
				bat "mvn verify -Pperformance"
				}
			}
		}
		
	}
}
