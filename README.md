# bhagya1[git1.txt](https://github.com/bhagya1994/bhagya1/files/8933941/git1.txt)
pipeline{

			agent any

			stages {
						stage('initialize') {
							steps{
								echo "hello jenkins"
							}
						}
						
						stage('build') {
							steps {
								echo "hello build"
							}
						}
						
						stage('deploy') {
							steps{
								echo "hello jenkins"
							}
						}
						
			}
}
