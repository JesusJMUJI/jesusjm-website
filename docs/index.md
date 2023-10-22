---
hide:
    - navigation
    - toc
icon: material/home
title: Página principal
---

## NOVEDADES

??? example "Versión actual: 1.1.1 (22/20/2023)"

    - [x] Corregidos errores de ortografía, gramática y legibilidad.
    - [x] Limpieza y simplificación de la instalación de VSCode con MikTex.
    - [x] TinyTex marcado como instalador no recomendado. 
    - [x] Añadidas algunas cosillas para hacer más amena la página.

    ??? failure "Versiones anteriores"
        
        Lista de cambios (1.1.0):

        * Rediseñada la página principal para contener la lista de cambios y el aviso.
        * Rediseñado el tutorial de instalación de MikTex.
        * Cambio de recomendación principal de VSCode a TexStudio.
        * Cambio de recomendación de compilador de TexLive a MikTex.

        Lista de cambios (1.0.4):

        * Informar de futuro cambio de documentación a [TexStudio](https://www.texstudio.org/).
        * Cambiar la tabla de contenidos a la derecha.

        Lista de cambios (1.0.3):

        * Añadidos iconos para editar la página.
        * Añadidos enlaces a la página de GitHub.
        * Añadido una fecha de edición al final de la página.
        * Aclarar panel de novedades.

        Lista de cambios (1.0.2):

        * Añadido un aviso de que la página está en construcción.
        * Añadir versión actual. 
        * Añadir reglas horizontales para separar secciones.
    
    [Commits](https://github.com/JesusJMUJI/recursos-uji/commits/main){.md-button}

??? success "Próximos cambios"

    - [ ] Añadir una sección para usar GitHub con LaTeX, y por extensión, GitHub Desktop.
    - [ ] Añadir un *about me* y como ayudar al desarrollo de la página.

---

## Instalación local de LaTeX en Windows, como alternativa a Overleaf

* ### [Instalación con TexStudio y MikTex](latex_install.md)

* ### [Instalación con VSCode y MikTex](latex_vscode.md)

!!! abstract "Pretexto"

    He creado este tutorial debido a los recientes cambios en [Overleaf](https://www.overleaf.com/blog/changes-to-free-compile-timeouts-and-servers) de los cambios en tiempo de compilación.
    Según Overleaf, no debería afectar a los usuarios debido a tiempos de compilación más rápidos; sin embargo, el tutorial asume que desconfías de Overleaf.

    Así que, este tutorial te enseñará a instalar un compilador de LaTeX en tu ordenador, con dos opciones dependiendo de lo que prefieras. Mediante el uso de [VSCode](https://code.visualstudio.com/) y [MikTex](https://miktex.org/download) o Tex Live, distribuido con [TinyTex](https://github.com/rstudio/tinytex-releases).
    También se da la opción de usar [TexWorks](#texworks), el cual viene incluido en MikTex y TexLive y es más sencillo de usar que VSCode.

    Si ves cualquier error en la página o quieres dejar alguna sugerencia, puedes escribir un issue en el repositorio de Github: <https://github.com/JesusJMUJI/jesusjm-website> o mandarme un mensaje privado por Discord.

    ??? warning "Aviso"
        Este tutorial asume que el lector dispone de conocimientos básicos sobre instalación y entendimiento sobre como usar VSCode e instaladores complejos. No obstante, se intentará explicar de la forma más sencilla posible. Además, se requiere de entender el inglés, ya que la mayoría de los programas están en inglés.
