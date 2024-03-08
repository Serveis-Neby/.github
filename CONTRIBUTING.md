# Clonar repositorios
```sh
git clone git@github.com:Serveis-Neby/repositorio.git
```
# Traer cambios
```sh
git pull --all
```
# Empezar desarrollar una tarea (el nombre de la rama debe seguir siempre la misma estructura)
```sh
git checkout develop
git checkout -b task/<num_task>-<nombre_tarea>
```
ejemplo:
```sh
git checkout -b task/37-implementing-user-authentication-middleware
```
# Subir cambios al stage
```sh
git add .
```
# Crear commit (los commits deben ser lo más pequeños y especificos posibles)
```sh
git commit -m "task #37: middleware acabado"
```
# Subir cambios
```sh
git push --all origin
```
# Fusionar cambios
Para fusionar los cambios se debe hacer SIEMPRE desde GitHub mediante un pull request
