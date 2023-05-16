## 0x1A. Application server
- DevOps
- SysAdmin
## Concepts
# For this project, we expect you to look at these concepts:
-<a href="https://intranet.alxswe.com/concepts/17"> Web Server</a>
- <a href="https://intranet.alxswe.com/concepts/67">Server</a>
- <a href="https://intranet.alxswe.com/concepts/68"> Web stack debugging</a>
# Background Context

Your web infrastructure is already serving web pages via Nginx that you installed in your <a href="https://intranet.alxswe.com/projects/266">first web stack project</a>. While a web server can also serve dynamic content, this task is usually given to an application server. In this project you will add this piece to your infrastructure, plug it to your Nginx and make is serve your Airbnb clone project.

## Resources
# Read or watch:
- <a href="https://www.nginx.com/resources/glossary/application-server-vs-web-server/">Application server vs web server</a>
- <a href="https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-gunicorn-and-nginx-on-ubuntu-16-04">How to Serve a Flask Application with Gunicorn and Nginx on Ubuntu 16.04 (As mentioned in the video, do not install Gunicorn using virtualenv, just install everything globally)</a>
- <a href="https://docs.gunicorn.org/en/latest/run.html">Running Gunicorn</a>
- <a href="https://werkzeug.palletsprojects.com/en/0.14.x/routing/">Be careful with the way Flask manages slash in route - strict_slashes</a>
- <a href="https://doc.ubuntu-fr.org/upstart">Upstart documentation</a>
## Requirements
# General
- A README.md file, at the root of the folder of the project, is mandatory
- Everything Python-related must be done using python3
- All config files must have comments
# Bash Scripts
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7-5~ubuntu16.04.1 via apt-get) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing


