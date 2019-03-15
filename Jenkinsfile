pipeline {
agent {
label 'LINUX'
}
stages {
stage ('Script') {
steps {
sh 'chmod +x rondoudou.sh'
sh './rondoudou.sh'
}
}
}
}
