# Modern Python developpement with Docker & Visual Studio Code

## Benefits :
- No more virtual environment needed (like virtualenv or pipenv)
- Easy installation/upgrade of Python version
- Easy setup of external services like a PostgreSQL database server
- Garanted compatibility of your packages with the chosen docker image distribution
  
## Prerequises :
- Virtualization enabled on your UEFI/BIOS
- On Windows & Mac OS : Docker desktop installed
- On linux : docker & docker-compose installed
- At least 8GB of RAM (16GB for more confort)
- Visual studio code with Remote-Containers extension installed
  
## 1. Create the project :
- Clone from a repo `git clone <repo URL> && cd <project-name> && code .`
or
- Start from scratch : `mkdir <project-name> && cd <project-name> && git init & code .`

## 2. Add the development container configuration files :
- `CTRL + SHIFT + P` > Remote-Container: Add Development Container Configuration files... > Python 3 > 3.10 > none > OK

## 3. Reopen in container :
- Reopen in container (if you see the popup)
or
- `CTRL + SHIFT + P` > Remote-Container: Open folder in container...

## 4. Eventually change the linter :
- `CTRL + SHIFT + P` > Python: Select Linter > flake8

## 5. Run your code :
- `python3 <file>`

## That's all ! Enjoy it :)
