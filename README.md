## Jiffy Plank

Quick project to learn FastAPI

### Development Environment Commands

Install pip and venv
```bash
sudo apt install python3-pip python3-venv
```
Create Python Virtual Environment
```bash
python3 -m venv DarkVenv
```
Start Virtual Python Environment
```bash
source ./DarkVenv/bin/activate
```
Install FastAPI in Virtual Python Environment
```bash
pip3 install "fastapi[standard]"
```
Start FastAPI Site
```bash
fastapi dev main.py
```
Stop Virtual Python Environment
```bash
deactivate
```
