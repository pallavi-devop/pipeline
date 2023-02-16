pipeline{

agent any
stages
{
stage ("buil")
{
steps {
sh 'mvn clean package'
}
post{

succes {
echo "Artifacts"

archiveArtifacts:'**/target/*.war'
}}
}
stage('Deploy to tomcat server')
{
}
}}

