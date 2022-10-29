pipeline {

	agent any 
	
    stage {
		stages("build") {
			steps{
				echo "Building my build file"
			}
		}
		
		stages("test") {
			steps{
				echo "Testing my application"
			}
		}
		
		
		stages("deploy") {
			steps{
				echo "Deploying my application"
			}
		}
		
		
	}
}

