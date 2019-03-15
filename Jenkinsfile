pipeline {
agent {
label 'LINUX'
}
stages {
stage ('Script') {
steps {
sh 'chmod +x roudoudou.sh'
sh './roudoudou.sh'
}
}
}
}
