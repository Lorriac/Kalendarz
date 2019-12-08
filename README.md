# Kalendarz
PWR_Kalendarz projekt kalendarz nierekurencyjny

# Logi
Logi znajdują się w pliku log.txt

# Instrukcja
Stwórz nowe wirtualne środowisko używając 

`virtualenv env`

Wejdź w środowisko:

`source ./env/bin/activate`

Zainstaluj django:

`pip install django`

Sklonuj repozytorum:

`git clone https://github.com/Lorriac/Kalendarz`

Wejdź w repozytorium Kalendarz:

`cd ./Kalendarz`

Zaaplikuj migracje:

`python manage.py migrate`

Uruchom serwer i wejdź pod 127.0.0.1:8000/calendar/

`python manage.py runserver`

# Dodawanie Zdarzeń
Dodajemy zdarzenie klikając 'Nowe Zdarzenie', data w formacie `yyyy-mm-ddThh:mm`, na przykład: 

`2019-12-08T18:00`

# Usuwanie Zdarzeń 
Tworzymy super usera:

`python manage.py createsuperuser`

Wchodzimy na 127.0.0.1:8000/admin/, logujemy się danymi podanymi podczas tworzenia superusera
W Events możemy usuwać, dodawać oraz edytować zdarzenia.

