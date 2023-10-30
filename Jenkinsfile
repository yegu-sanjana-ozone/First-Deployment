node {
   DOCKER_PATH = sh (script: 'command -v docker', returnStdout: true).trim()
   echo "Docker path: ${DOCKER_PATH}"
   
   FREE_MEM = sh (script: 'free -m', returnStdout: true).trim()
   echo "Free memory: ${FREE_MEM}"
   
   echo sh(script: 'env|sort', returnStdout: true)

}
