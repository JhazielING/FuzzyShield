# FuzzyShield

Proyecto web hecho con Django con tres páginas: inicio, login y panel.

## Cómo ejecutar el proyecto

1. Crear el entorno virtual:
   ```bash
   python -m venv venv
   ```
2. Activarlo:
   ```bash
   # Windows
   venv\Scripts\activate
   # Mac/Linux
   source venv/bin/activate
   ```
3. Instalar las dependencias:
   ```bash
   pip install -r requirements.txt
   ```
4. Correr el servidor:
   ```bash
   python manage.py runserver
   ```
5. Abrir en el navegador `http://127.0.0.1:8000/`

## Rutas

- `/` inicio
- `/login/` iniciar sesión
- `/panel/` panel