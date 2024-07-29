
![Logo](https://ik.imagekit.io/wtj3he3ncnq/New%20Project_P7lVmAPi-.png)


# Jenkins-Cpanel

This repo is all about how we can create a CI/CD pipeline for the Angular project to live on Cpanel using the Jenkins.


## Requirements

1. A ssh tunnel connection between jenkins and cpanel using pem or ppk file.


## Prerequisites in jenkins
1. Plugins are required in jenkins.
    - Git Plugin
    - Global Slack Notifier Plugin
    - Slack Notification Plugin Version
    - File Operations
    - SSH Credentials
    - Publish Over SSH
    - SSH Plugin


## Features

- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform


## Authors

- [@shivkantbaghel](https://github.com/shivkantbaghel)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Stages Explanation

Stage 

```bash
  stage('Notify Start') {
            steps {
                script {
                    slackSend(channel: "${params.channel}", message: "Build Started: \nProject: ${params.project_name} \nBranch: ${params.branch_name} \nLink: ${params.remote_url}", tokenCredentialId: "${params.workspace_credential}")
                }
            }
        }
```


## 🚀 About Me
I'm a full stack developer...


# Hi, I'm Katherine! 👋


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)

