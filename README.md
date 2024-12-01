# Versionamiento
● Evidencia de producto: GA7-220501096-AA1-EV01 herramientas de versionamiento (GIT) instalada y configurada.
Tomando como referencia el componente formativo “Integración continua”, conectar el equipo local con el repositorio remoto por medio de Git usando los comandos vistos anteriormente.
Realice la ejecución de cada uno de los comandos básicos de git remoto y local teniendo en cuenta el ejercicio propuesto a continuación:
Paso 1
1. Crear un nuevo repositorio público en GitHub, gitLab o herramienta de su selección con el nombre Programa-git.
2. Añadirlo al repositorio local del Programa.
3. Mostrar todos los repositorios remotos configurados.
Paso 1
# Crear el repositorio en GitHub y copiar su url con el protocolo https. > git remote add github url
> git remote -v
Paso 2
1. Agregar los cambios del repositorio local al repositorio remoto de GitHub o GitLab.
2. Acceder a GitHub o GitLab y comprobar que se han subido los cambios mostrando el historial de versiones. >git push github master
Paso 3 ● Agregar el archivo kotlin.txt que contenga el nombre del usuario y su correo electrónico.
● Agregar los cambios.
● Realizar un commit con el mensaje “Añadido datos.”
● Cargar cambios al repositorio remoto.
GFPI-F-135 V01
> cat > kotlin.txt
git add . > git commit -m
"Añadido datos." > git push origin master.
