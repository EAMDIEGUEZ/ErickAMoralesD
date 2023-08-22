# ErickAMoralesD
Comandos Terminal

drwxr-xr-x
irwxr-xr-x

i= symbolic league
d= directorio
r= read
w= write
x= execute

rwx= permisos de usuario principal
r-x= permisos de staff
r-x= permisos de todos

^ = carat
cd = change directory (regresar a home)
cd xxxx = change directory to xxxx (only for directories)
ls = lists (muestra el contenido del directorio)
pwd = print working directory (muestra dónde te hallas)
cd .. = regresar un nivel
ls -l = ver contenido de donde estás
ls -l xxxx = ver el contenido de la carpeta xxxx
mv xxxx(archivo) xxxx(carpeta) = mueve archivo a carpeta 
mv xxxx(carpeta/archivo) xxxx(carpeta/archivo) = cambia el nombre de la carpeta/archivo
nano xxxx = crear un archivo de nombre xxxx
mkdir xxxx = crear carpeta
cat = mostrar el contenido de algo (para archivos)
cat /etc/xxxx = mostrar contenido
> redireccionar la salida (mandar a lo que se escriba después) 
cat /etc/xxxx > xxxx = redireccionamiento de grupo a xxxx
Root = super user
ls -|R | grep xxxx = busca xxxx en el sistema

Git commands
•**git clone**; download a repository to the local machine
git clone curls

**git status**: check the current situation of the local repository
git status

**git add**: add files to the staging area before commiting
 git add <files git add

**git commit**: register the changes into the history of the repository
git commit -m "message"

** git push**: send local changes to github
git push origin main 
