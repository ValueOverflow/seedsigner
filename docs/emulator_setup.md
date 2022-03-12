# Emulator Setup

## Create/Enter virtualenv
```
mkvirtualenv seedsigner-gui
```

## Pip installs
```
pip install -r requirements.txt
```

## Install Tkinter
```
sudo apt install python3-tk
```

## Run the emulator
```
cd seedsigner/src
NOTAPI=true python3 main.py
```