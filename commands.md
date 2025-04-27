**Inicializando el repositorio**
git init

**Verificar el estado de los archivos**
git status
git status -s

**agregando los archivos al repositorio**
git add <nombrearchivo>
git add .
git add --all

**Agregamos cambios al repositorio LOCAL y un comenatrio del cambio**
git commit -m

**subiendo los cambios al repositorio remoto**
git push origin <ramaprincipal>

### Comandos Adicionales
**configuracion de usuario**
git config user.name
git config user.email

git config user.name <usuario github>
git config user.email <correo github>

**verificando repositorio remoto**
git remote -v

**agregando repositorio remoto**
git remote add origin <enlacerepositoriogithub>