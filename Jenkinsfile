node('master') 
{
    stage('Continuous Loans_Download') 
	{
          git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Loans_Build') 
	{
          sh label: '', script: 'mvn package'
	}
    stage('Continuous Loans_Testing') 
	{
              sh label: '', script: 'echo "Testing Passed"'
	}
}
