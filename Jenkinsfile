node {
    stage('Checkout') {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '3a109c81-f97c-46a3-827e-8da90288dae4', url: 'https://github.com/cmoseses/playground.git']]])
    }

    stage('build') {
        echo 'helloworld'
    }
}
