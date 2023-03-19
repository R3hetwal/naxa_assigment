1. Create `python environment`
```shell
python -m venv env
```
2. Activate python virtualenv

3. Run package install
```shell
pip install -r requirements.txt
```
4. Run folling comand 
```shell
python manage.py makemigrations
```
```shell
python manage.py migrate
```
5. Run
```shell 
`python manage.py runserver `
```
6. Open up
```shell
 `http://127.0.0.1:8000/api/v1/docs` 
 ```