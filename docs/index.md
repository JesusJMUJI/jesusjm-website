---
icon: material/home
title: Página principal
hide:
    - navigation
---

## NOVEDADES

??? info "Versión actual: 1.1.0 (22/20/2023)"
    
    * Rediseñada la página principal para contener la lista de cambios y el aviso.
    * Rediseñado el tutorial de instalación de MikTex.
    * Cambio de recomendación principal de VSCode a TexStudio.
    * Cambio de recomendación de compilador de TexLive a MikTex.

    ??? info "Versiones anteriores"
        
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

---

## &darr; AVISO &darr;

!!! warning "PÁGINA EN COSTRUCCION"

    Planeo añadir nuevas herramientas y cambios a esta página, asi que se considera como no finalizada.

    * Simplificar el proceso de instalación.
    * Añadir una sección para usar GitHub con LaTeX, y por extensión, GitHub Desktop.
    * Resaltar en negrita las palabras principales siguiendo el criterio de lectura.

---

## Instalación local de LaTeX en Windows como alternativa a Overleaf

!!! note "Pretexto"

    He creado este tutorial debido a los recientes cambios en [Overleaf](https://www.overleaf.com/blog/changes-to-free-compile-timeouts-and-servers) de los cambios en tiempo de compilación. 
    Según Overleaf, no debería afectar a los usuarios debido a tiempos de compilación más rápidos; sin embargo, el tutorial asume que desconfías de Overleaf.

    Así que, este tutorial te enseñará a instalar un compilador de LaTeX en tu ordenador, con dos opciones dependiendo de lo que prefieras. Medianteel uso de [VSCode](https://code.visualstudio.com/) y [MikTex](https://miktex.org/download) o Tex Live, distribuido con [TinyTex](https://github.com/rstudio/tinytex-releases).
    También se da la opción de usar [TexWorks](#texworks), el cual viene incluido en MikTex y TexLive y es más sencillo de usar que VSCode.

    Si ves ualquier error en la página o quieres dejar alguna sugerencia, puedes escribir un issue en el repositorio de Github: <https://github.com/JesusJMUJI/jesusjm-website> o mandarme un mensaje privado por Discord. 

    ??? warning "Aviso"
        Este tutorial asume que el lector dispone de conocimientos básicos sobre instalación y entendimiento sobre como usar VSCode e instaladores complejos. No obstante, se intentará explicar de la forma más sencilla posible. Además, se requiere de entender el inglés, ya que la mayoría de los programas están en inglés.

* ### [Instalación local de LaTeX con TexStudio](latex_install.md)

    [Button](latex_install.md/#texstudio){.md-button}

* ### [Instalación local de LateX con VSCode y TinyTex](vscode_taex.md)