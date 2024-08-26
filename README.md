# VENV-Instructions
Instructions to create a virtual environment in Python

Running Python Project
```
mkdir -p /data/cache
```

Create a python virtual environment:

```
mkdir -p /data/USERNAME
cd /data/USERNAME
python3 -m venv --system-site-packages ./VENVNAME
source ./VENVNAME/bin/activate
```

Install your packages:

```
pip3 install <package-name> --cache-dir /data/cache
```

The pip command can be changed to download the packages from requirements file :

```
pip3 install -r requirements.txt --cache-dir /data/cache
```

Activate this virtual env before running your project.

Terminal - To activate virtual env in vscode, follow below guidelines:

```
source /data/USERNAME/VENVNAME/bin/activate
```
