pipeline{
    agent any
    triggers {
      pollSCM 'H/1 * * * *'
    }
    stages{
        stage("SCM"){
            steps{
               echo "job ran.....again and again"
            }
        }
    }
}
