node('built-in') 
{
    stage('Continuous Download on master') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build on master') 
	{
    sh label: '', script: 'mvn package'
	}

}
