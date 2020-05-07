@Library('jen-pipe-lib@master') _

pipeline
{
	stages
	{
		stage('from jenkinsfile')
		{
			steps
			{
				echo "from jenkinsfile..."
			}
		}
		stage('from lib')
		{
			steps
			{
				fromLibarary()
			}
		}
	
	}
}

