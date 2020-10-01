![](https://github.com/Pinzauti/indagine-edit-api/workflows/Django%20CI/badge.svg)
![](https://github.com/Pinzauti/indagine-edit-api/workflows/Lint%20Code%20Base/badge.svg)
![](https://github.com/Pinzauti/indagine-edit-api/workflows/CodeQL/badge.svg)
[![Build Status](https://travis-ci.com/Pinzauti/indagine-edit-api.svg?branch=master)](https://travis-ci.com/Pinzauti/indagine-edit-api)
[![BCH compliance](https://bettercodehub.com/edge/badge/Pinzauti/indagine-edit-api?branch=master)](https://bettercodehub.com/)
## Informazioni sul progetto
Indagine EDIT si pone l'obiettivo di rendere fruibili i dati raccolti dalla regione Toscana in materia di incidenti stradali.
## Guida all'utilizzo

### Prerequisiti

- [Python](https://www.python.org/)

### Installazione
- Impostare la variabile di ambiente `SECRET_KEY`.
- Impostare la variabile di ambiente `ALLOWED_HOSTS` con l'indirizzo ip del backend.
- Avviare un virtual enviroment (e.g. [venv](https://docs.python.org/3/library/venv.html)).
- Eseguire `pip install -r requirements.txt`.

### Avvio
- Eseguire `python manage.py runserver`.
