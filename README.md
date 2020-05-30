1. Here we are doing the build, dockerization of app to a dockerimage is done through a single Dockerfile, we can do it with build as a seperate stage in our CICD as well
2. In our case we are using dotnet's native framework/webserver "Kestrel web server" we can use other webservers like IIS or nginx
Note: deployment.yml needs indentation correction
