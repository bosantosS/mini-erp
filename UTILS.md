# UTILS

## Crear proyecto con django

```bash
cd mini-erp
.\Scripts\activate
python -m django --version
pip install django
django-admin startproject mini_erp
cd mini_erp
python manage.py runserver
```

## Crear aplicaciones principales

```bash
cd ..\mini-erp\mini-erp\mini_erp
python manage.py startapp produccion #Ejemplo
```

## Registrar aplicaciones

```python
# mini_erp\mini_erp\settings.py
# INSTALLED APPS = [...'produccion',...]
```

## Ejecutar migraciones para la bd

```bash
cd ..\mini-erp\mini-erp\mini_erp
python manage.py migrate
```

