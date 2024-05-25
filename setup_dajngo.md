# Setup Python Virtual Environment for Best Development Experince

### Python itself comes with venv for managing environments which we will use for this guide. To create a virtual environment for your project, open a new command prompt, navigate to the folder where you want to create your project and then enter the following:

> To create Python Virtual Environment:
```bash
py -3 -m venv venv_name
```

### To activate the environment, run: (If you can not activate the virtual enviroment, you need to Kill the Terminal and type in below command again)

> To activate the environment, run:
```bash
venv_name\Scripts\activate.bat
```

#### The virtual environment will be activated and you’ll see “(venv_name)” next to the command prompt to designate that. Each time you start a new command prompt, you’ll need to activate the environment again.

# Installing Django Web Framework

### Once you've created a virtual environment, and activated it, you can use pip3 to install Django.

```bash
# Windows
pip3 install django~=4.2
```

### You can test that Django is installed by running the following command (this just tests that Python can find the Django module):

```bash
# Windows
django-admin --version
```

# Create Django Project
### After you got Django Module installed in your Computer now it is time to create the Project:
1. Create a Folder to store the project.
2. Create [Virtual Enviroment](https://github.com/SosSokleng99/Github-Cheatsheet/blob/main/setup_dajngo.md#setup-python-virtual-environment-for-best-development-experince).
3. Activate the Virtual Enviroment.
4. To create Django Project, run:
```bash
# Windows
python3 django startproject project_name
```

# Create a Django App

### After you create Django Project, we need to create a APP inside Django Project which is one of many feature for the Project:
```bash
# Windows
python3 manage.py startapp app_name
```

> Start Django Server, run:
```bash
python3 manage.py runserver

#CONTROL + C to stop server
```
