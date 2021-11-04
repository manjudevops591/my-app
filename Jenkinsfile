pipeline{
    agent any
    triggers {
      pollSCM 'H/15 * * * *'
    }
    stages{
        stage("SCM"){
            steps{
               echo "job ran.....again and again"
            }
        }
    }
}
