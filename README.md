# innovatica

## Desarrollo (Solo para desarrollar la app)

python -m venv venv
pip install -r requirements.txt

## Ejecucion (Solo para ejecutar y probar)

docker build -t innovatica-app .
docker run -d -p 8000:8000 innovatica-app

Acceso App por http://localhost:8000
Acceso Admin por http://localhost:8000/admin

Usuario: admin
Contrasena: admin