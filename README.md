# Opis aplikacji  
## 1. Wymagania  
- python 3.10+
- django min.5.0
- paczka Pillow
- silnik bazy sqlite3

## 2. Uruchomienie projektu
Wykonanie polecenia  
Dla Windows  
```sh
python -m venv venv
```
Dla Unix  
```sh
python3 -m venv venv
```
Uruchomienie wirtualnej zmiennej środowiskowej (venv)  
Dla Windows  
PowerShell
```sh
.\venv\Scripts\activate
```
lub
```sh
source venv/Scripts/activate
```
Instalacja Django  
```sh
pip install django
```
Instalacja Pillow
```sh
pip install Pillow
```

(Opcjonalnie jeżeli jest pusta baza to)
```sh
python manage.py migrate
```
oraz stworzenie superusera
```sh
python manage.py createsuperuser
```

W przypadku używania silnika sqlite3 z repo dane do logowania

```sh
login: xman  
password: qwerty2023
```
Uruchomienie serwera  
```sh
python manage.py runserver
```
