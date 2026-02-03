# Jenkins Shared Library (Simple)

Steps:
- javaProject(skipTests: true, image: 'my-app')
- pythonProject(skipTests: false, image: 'my-app')

Optional:
- Set SONAR_SERVER in Jenkins to enable Sonar stage
