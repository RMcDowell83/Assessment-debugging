## Programmer Assessment Q4

This repository contains a broken web app built with Dash. Please follow the tasks below.

Tasks:
1. Clone this repo to your machine.
2. Fix missing dependencies and fill authors section in `pyproject.toml`.
3. Fix bugs prevent the app `main.py` from running.
4. Change port the app ruuning on to `10030`.
5. Commit you changes.
6. Update `README.md` with a instruction
   1. Assuming the user has a fresh minimum Linux installation with no python.
   2. Setup python and virtual environment for this app, remember to use the fixed `pyproject.toml`.
   3. How to run this app and how to access it without portforwarding.
7. Push all the changes to your own repository on Github, and provide a link to your own repo in your submission in the last.

## Setup Instructions
   1. Install Python:
```
sudo apt update
sudo apt install python3
sudo apt intall python3-pip
```
   2. Setup A Virtual Enviornment:
```
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install e .
```
   3. Run the Application:
```
python main.py
```
   To Access The Application Use the URL:
```
http://127.0.0.1:10030/
```
   
