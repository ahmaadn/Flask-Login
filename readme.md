## Setting virtual environment
Silahkan membuat virtual environment python 
```bash
py -m venv .venv
```
Aktifkan Virtual environment
```bash
.venv\Scripts\activate.bat
```
Install Package
```
pip install -r requirements.txt
```
Kemudian buat database
```
py create_db.py
```
Run Server
```
flask run
# debug
flask --app app --debug run
```

Buka Browser ketikan url http://127.0.0.1:5000 ketika sudah di run 
