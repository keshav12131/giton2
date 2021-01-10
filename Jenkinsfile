pipeline{
 agent any
  stages{
    stage (build){
    steps{
     bat 'echo "Hello updated"'
    }
    }
  }
 post{
 failure{
  bat 'echo "Failedddd"' 
 }
 }
}
