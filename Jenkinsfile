node {
    stage('SCM') {
	echo 'Gathering code from version control'
        git branch: '${branch}' , url: 'https://github.com/mravind3r/jenkins-groovy.git'
    }
    stage('Build') {
        echo 'Building....'
        echo ' new build feature...'
    }
    stage('Test') {
        echo 'Testing....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
