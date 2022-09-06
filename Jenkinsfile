pipeline{ 

agent any

stages {
	stage ('SCM') {
		steps {
				echo "git pull code"
			}	
}


	stage ('Deploy') {
		steps {

			 echo "delploy code"
		}
}


	stage ('Test') {
		steps{ 
		
			echo "test code"
		}
	}

}

}