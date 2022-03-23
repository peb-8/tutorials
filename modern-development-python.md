# Modern Python developpement with Docker & Visual Studio Code

## Benefits :
- No more virtual environment needed (like virtualenv or pipenv)
- Easy upgrade of Python version
- Garanted compatibility of your packages with the chosen docker image distribution
  
## Prerequises :
- On Windows : Docker desktop installed
- On linux : docker & docker-compose installed
- At least 8GB of RAM (16GB for more confort)
- Visual studio code with Remote-Containers extension installed
  
## 1. Create the project :
- Clone from a repo `git clone <repo URL> & cd <project-name> & code .`
or
- Start from scratch : `mkdir <project-name> & cd <project-name> & git init & code .`

## 2. Add the development container configuration files :
CTRL + SHIFT + P > Remote-Container: Add Development Container Configuration files... > Python 3 > 3.10 > none > OK

## 3. Reopen in container :
CTRL + SHIFT + P > Remote-Container: Open folder in container...

## 4. Enjoy !
