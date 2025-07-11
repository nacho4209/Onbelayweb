"# Onbelayweb" 



### Git Flow 

- `main`: Rama de producción (no se toca directamente).
- `develop`: Rama de desarrollo donde se hace merge de todas las features.
- `feature/nombre`: Ramas para cada nueva funcionalidad o cambio.



1. Crear una rama desde develop:
   
   git checkout develop
   git pull origin develop
   git checkout -b feature/nombre-de-la-feature


2. Trabajar, commitear y luego hacer merge:

   
   Copiar
   Editar
   git add .
   git commit -m "Lo que se hizo"

3. Hacer merge a develop:

   git checkout develop
   git pull origin develop
   git merge feature/nombre
   git push origin develop

4. Borrar rama si se desea:

   git branch -d feature/nombre
   git push origin --delete feature/nombre

