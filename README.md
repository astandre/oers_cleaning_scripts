# Scripts de limpieza de tripletas extraidas de OERS


# Guia de migracion
## Instalar python

Instalar la version de Python 3.5+

## Requerimientos
Instalar todos los requerimientos encontrados en el archivo requirements.txt

```
pip install requirements.txt
```

En caso de existir problemas con el libreria mysqlclient, intentar el comando para instalarla

```
pip install --only-binary :all: mysqlclient 
```
## Archivos
### Freeboks
En el archivo *freeBooks_cleaning.ipynb* sirve para limpiar los datos obtenidos de https://open.umn.edu/opentextbooks

 

### BC Campus
En el archivo *bccampus_cleaning.ipynb* sirve para limpiar los datos obtenidos de https://open.bccampus.ca
