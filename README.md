# Gitpod's OpenVSCode Server
Deploy Gitpod's VSCode Webserver on Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)


Manual deploy:
- [Connect your GitHub account to your Render account](https://render.com/docs/github).
- Clone this repo.
- Create a new web service using this repo and the following parameters:
  - Environment: Docker
  - Advanced > Add Environment Variable
    - key: SERVER_VERSION 
    - value: v1.59.0
  - Advanced > Add Disk
    - Name: data
    - Mount Path: /home/workspace
- Watch your VSCode Webserver deploy, and then log in at the public URL listed below your web service name.
