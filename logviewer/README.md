#### Clone Repo
```
git clone https://github.com/DirtyOptics/kismet-logviewer.git
```

#### Check and make sure it cloned, Copy yout .kismet file to log folder.
```
cd kismet-logviewer/logviewer/
```

#### Create python virtual environment
```
sudo python3 -m venv kismet
```

#### Activate 'kismet' virtual environment
```
source kismet/bin/activate
```

#### You may need to change permissions of the pulled folder:
```
sudo chown -R $(whoami) /home/user/kismet
```

#### Install the items from inside requirements.txt
```
pip install -r requirements.txt
```







This thing uses Django

copy your kismet log file (ends in .kismet) to "logs" then run:

```
python manage.py runserver 0.0.0.0:8000
```

