# aux03

## Seteando el ambiente virtual
```
python -m venv ev
ev\Scripts\activate
```
Nota: En caso de MacOS para activar el ambiente virtual el comando es `source ev/bin/activate`

## Instalando Django
```
pip install django
pip freeze > requierements.txt
```

## Creando el proyecto
```
django-admin startproject nombre_proyecto
```
Nota: Reemplazar `nombre_proyecto` por el nombre deseado

## Creando una aplicación
```
cd nombre_proyecto
python manage.py startapp nombre_app
```
Nota: Reemplazar `nombre_app` por el nombre deseado

## Corriendo el proyecto
```
python manage.py runserver
```
