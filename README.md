![Jenkins Pipeline Flow](https://raw.githubusercontent.com/Bhattu-Sai-Praneeth/Jenkins-pipeline/main/Flow.png)

# Jenkins Pipeline Overview

This Jenkins pipeline automates the deployment of a Java web application. The steps are as follows:

1. **Get Code**  
   Fetches the Java project from the GitHub repository.

2. **Build App**  
   Uses Maven to compile the code and package it into a `.war` file.

3. **Approve**  
   Waits for a user to manually approve the deployment.

4. **Deploy**  
   Pushes the built `.war` file to a remote Tomcat 9 server.

## Pipeline Flow

