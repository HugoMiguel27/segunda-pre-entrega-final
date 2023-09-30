# Orient®

Un proyecto para una empresa real que se dedica a preparar aspirantes a diferentes campos de estudio, enseñándoles temas básicos de sus futuras carreras para que puedan tener una ventaja profesional.

###Código utilizado:

- HTML
- CSS y SASS

###Otras cosas aplicadas en este proyecto:
- SEO
- Keyframes
- Animaciones
- Mixins
- Extends
- Fragmentaciones
- Pseudoclases y Pseudoelementos




####EJEMPLO DE CÓDIGO HTML 

```html
<section class="barra-de-navegacion">
            <div class="logo-esquina">
                <a href="./index.html"><img src="./assets/imagenes/home.png" alt="Inicio"></a>
            </div>
            <div>
                <nav class="nav-cursos">
                    <ul>
                        <li><a href="./pages/cursos.html">Cursos</a></li>
                        <li><a href="./pages/examenes.html">Exámenes simulacro</a></li>
                        <li><a href="./pages/material.html">Material</a></li>
                        <li><a href="./pages/contacto.html">Contacto</a></li>
                    </ul>
                </nav>
            </div>
        </section>
```

####EJEMPLO DE SASS 

```sass
.whatsapp-contacto {
            display: flex;
            grid-area: WhatsApp;
            color: white;

            button {
                background-color: #535353;
                border-radius: 1.25rem;
                box-shadow: none;
                padding: .3125rem 2.5rem;

                a {
                    img {
                        width: 4.375rem;
                        padding-bottom: .625rem;
                    }

                    p {
                        font-family: 'Quicksand', sans-serif;
                        font-size: 1.5625rem;
                        font-weight: 700;
                        color: orange;
                    }

                    p::first-letter {
                        color: white;
                        font-size: 1.875rem;
                    }
                }

            }

            button:hover {
                background-color: #9ebcbf;
            }
        }
```
