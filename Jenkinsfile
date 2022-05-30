node('built-in') 
{
    stage('Continuous Download on branch') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build on branch') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
