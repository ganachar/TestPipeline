pipeline{
    agent any
    environment{
        Toolname = "Jenkins"
    }
    stages{
        stage('condition'){
            steps{
                script{
                if(Toolname == "Jenkins")
                echo "Our CI CD Tool"
                else
                echo "Not our CI CD Tool"
            }
            }    
        }
    }
}
