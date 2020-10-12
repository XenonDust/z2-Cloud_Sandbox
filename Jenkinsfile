
pipeline {
    agent any

    stages {
        stage('Get from Git') { 
		steps {
        git 'https://github.com/XenonDust/z2-Cloud_Sandbox.git'
		}
    }
    stage('Build') {
        steps {
        powershell 'deffPwsh.ps1'
		}
    }
    stage('Results') {
		steps {
        bat 'echo "Done?"'
		}
    }
    }
}
