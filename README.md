# Pasos para subir código a Github

### Nota: Ya configuramos lo esencial, ahora solo:  
1. Por medio de la terminal **Bash** (Windows es GitBash, MacOS es la terminal zsh o Bash) ir al directorio con el código.  
2. Inicializar repositorio `git init`  
3. Por medio del IDE (Pycharm), crear archivo `.gitignore` en la raíz de nuestro proyecto.
4. Ir a [https:gitignore.io](https://gitignore.io), escribir 'Python' que es para la tecnología que ocupamos y lo copiamos.  
5. Regresar a nuestro IDE (Pycharm) y en el archivo `.gitignore`, pegar el texto, en las últimas líneas del código, quitarle el '#' a #.idea/ .
6. Regresar a la terminal y agregar nuestro archivos: `git add .`
7. Establecer **"main"** branch: `git branch -M main`
8. Hacer commit (preparar) nuestro código: `git commit -am "Mensaje aquí relacionado con los cambios."`  
9. Crear un nuevo repositorio en Github, una vez creado, cliquear en la botón **"ssh"** para que nos dé el código apropiado.
10. En la terminal establecer branch (rama) remota copiando el enlace de la casilla "ssh" de la página de inicialización de tu repositorio en Github.
11. Hacer push (subir) nuestro código. La primera vez en un repositorio nuevo es:`git push -u origin main`  
    Las siguientes veces simplemente hacemos push con: `git push origin main`