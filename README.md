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




   ## Rama: feature/landing-improvements

Se han hecho los siguientes cambios:

- Cambiado el logo principal (`logo.serio.tagline.svg`)
- Nuevo tagline: "De escaladores para escaladores"
- Imágenes de App Store y Play Store nuevas (SVG)
- Animaciones para fade/slide al cargar contenido
- Mejora visual responsive (logos más grandes en desktop, optimizados en móvil)

### Git Flow usado:

- Cambios aplicados en `feature/landing-improvements`
- Listo para hacer merge a `develop`


