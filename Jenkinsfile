node{
    stage('Git Checkout'){
        git 'https://github.com/rishumathur/NAGPDevOpsProject.git'
    }
	stage('Echochekout')
	{
	 echo 'checkout completed'
	}
    stage('Build'){
        bat 'mvn clean verify sonar:sonar -Dsonar.projectKey=SonarProject2 -Dsonar.host.url=http://localhost:9000  -Dsonar.login=b0a42ca3d697420daa76a623da18f96e473c2021'
    }
	stage('finished')
	{
	 echo 'checkout completed'
	}
}
