node('feature') 
{
    stage('Continuous Download_Loans') 
	{
    git 'https://github.com/Chowdeswar777/multibtranch-project.git'
	}
    stage('Continuous Build_Loans') 
	{
    sh label: '', script: 'mvn package'
	}
  
}
