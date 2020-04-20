node{   
     Stage('SCM checkout'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'aa325c0a-16fe-40ae-8f2f-80d1b58752a6', url: 'https://github.com/sanbar-web/maven.git']]])
     }    
}
