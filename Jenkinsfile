pipeline{
    agent any
    
    stages{
        stage("Code clone"){
            steps{
                echo "this is cloning the code"
                clone("https://github.com/ashwinibajanghate/Django_Notes_App.git","main")
            }
        }
        stage("Code Build"){
            steps{
                echo "this is building the code"
            }
        }
        stage("Push to DockerHub"){
            steps{
               echo "this is image push to dockerHub"
            }
        }
        stage("Deploy"){
            steps{
                echo "this is deploying and running the container "
            }
        }
        
    }
}
