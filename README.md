# ml_project
Practice ML Project

## Start ML Project

### Software and Account Requirements

1. [Github Account](https://github.com)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT Cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)

Cloning a Repository from Github
'''
git clone <link_url>
'''

Creating Conda Environment
'''
conda create -p venv python=3.7 -y
'''

Activating Environment
'''
conda activate venv/
'''

For installing libraries
'''
pip install -r requirements.txt
'''

For updating all files in Git
'''
git add .
'''

For checking versions in git
'''
git log
'''

To create version/commit all changes to git
'''
git commit -m "message"
'''

To send the version update to github page
'''
git push origin main
'''

To check remote url
'''
git remote -v
'''

To see difference in current edit and previous version
'''
git diff
'''

HEROKU Setup

1. HEROKU_EMAIL = xxxxxxxx
2. HEROKU_API_KEY = xxxxxxxx
3. HEROKU_APP_NAME = xxxxxxxx

Build Docker Image
'''
docker build -t <image_name>:<tag_name> .
'''
> Note: Image Name for docker should always be lowercase

To list docker image
'''
docker images
This will give Image ID of project
'''

Run Docker Image
'''
docker run -p 5000:5000 -e PORT=5000 <Image ID>
'''

To check docker container running
'''
docker ps
This has container id
'''

To stop docker container
'''
docker stop <container id>
'''
