node('built-in') 
{
    stage('Continuous Download_feature') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_feature') 
	{
    sh label: '', script: 'mvn package'
	}
}
