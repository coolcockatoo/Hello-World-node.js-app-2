# References
https://code.visualstudio.com/docs/devcontainers/create-dev-container#_dockerfile
# Pre requisites:
Install Docker https://docs.docker.com/desktop/
Install VS Code: https://code.visualstudio.com/
Download Dev Containers extenstion in Visual Studio Code
# Steps
1. Create a new folder for the project
2. Create a devcontainer.json file within the project
3. Run Dev Containers: Reopen in Containers 
4. Rename the devcontainer.json file outside of devcontainer to app.js
5. Add console.log("Hello World"); to app.js
6. Run node app.js in terminal and it will return "Hello World"
