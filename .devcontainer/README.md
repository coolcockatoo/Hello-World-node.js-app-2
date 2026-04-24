# References
https://code.visualstudio.com/docs/devcontainers/create-dev-container#_dockerfile
# Pre requisites:
Install Docker https://docs.docker.com/desktop/
Install VS Code: https://code.visualstudio.com/
Download Dev Containers extenstion in Visual Studio Code
# Steps
1. Create a new folder for the project
2. Create a devcontainer.json file within the project
3. Run Dev Containers: Reopen in Container, and after the project restarts you will see this <img width="451" height="168" alt="image" src="https://github.com/user-attachments/assets/Adda3aa3741-aab8-4ad1-a197-de6af27f04e8" />
4. Rename the devcontainer.json file outside of devcontainer to app.js
5. Add console.log("Hello World"); to app.js
6. Run node app.js in terminal and it will return "Hello World"
