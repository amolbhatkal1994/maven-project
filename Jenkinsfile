pipeline
{
agent any
stages
{
stage('scm checkout')
{
    steps{git 'https://github.com/amolbhatkal1994/maven-project.git'}
}
stage('unit test case')
{
    steps{withMaven(maven: 'HOME') 
    {
    sh 'mvn test'}
    }
}
}
}
