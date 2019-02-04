node('master') 
{
    stage('Cont_downloasd') 
    {
       git 'https://github.com/selenium-saikrishna/maven.git'
    }
    stage('Cont_build_masters') 
    {
       sh label: '', script: 'mvn package'
    }
    }
