## source : https://nomadcoders.co/fullstack-gpt/lectures
### Docker Command
#### build : docker build -t paduck86/fullstack-gpt:tag .
#### debug : docker run -d -p 3000:3000 -v $PWD:/usr/src/app paduck86/fullstack-gpt:latest
#### go inside the docker ps : docker exec -it [container_id_or_name] /bin/bash


### 1. Make Virtual environment
#### python3 -m ./env
#### source ./env/bin/activate
#### add env folder to .gitignore

### 2. Install requirements
#### pip3 install -r requirements.txt
