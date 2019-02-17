pipeline{
	agent any
	stages {
		stage('Test'){
			step{
				sh './gradlew check'
}
}
}
	post{
		always{
			junit 'build/reports/**/*.xml'
}
}
}
