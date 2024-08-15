
```
git clone https://github.com/DirtyOptics/kismet-logviewer.git
```

```
cd kismet-logviewer/logviewer/

```
python3 -m venv kismet
```

```
source kismet/bin/activate

```

```
pip install -r requirements.txt
```







This thing uses Django

copy your kismet log file (ends in .kismet) to "logs" then run:

python manage.py runserver 0.0.0.0:8000


