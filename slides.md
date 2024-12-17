---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# https://cover.sli.dev
background: https://img.freepik.com/vector-gratis/fondo-tecnologia-degradado-purpura_23-2149118850.jpg
title: Welcome 
info: |
  ## Presentación Git.

  Learn more at [Sli.dev](https://sli.dev)
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Desde Git a la Web en Pulpoline

 con GitHub Actions y GitHub Pages


<div class="abs-br m-6 text-xl">
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: image-right
backgroundSize: contain
image: https://img.freepik.com/vector-gratis/mini-personas-dispositivos-electronicos_24877-56572.jpg
---

# ¿Qué es Git?

- Sistema de control de versiones distribuido.
- Rastrea cambios en archivos a lo largo del tiempo.
- Permite colaborar en proyectos de manera eficiente.
<br>
<br>

Leer más [¿Qué es Git?](https://docs.github.com/es/get-started/start-your-journey/about-github-and-git)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/features/slide-scope-style
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
level: 2
layout: image-right
backgroundSize: contain
image: https://img.freepik.com/vector-gratis/servicio-alojamiento-web-cadenas-informacion-gestion-contenidos-redes-conexion-sincronizacion-servidor-internet-almacenamiento-datos_335657-830.jpg
---

# ¿Qué es GitHub Actions?

- Herramienta de automatización para construir, probar y desplegar software directamente desde GitHub.
- Permite crear workflows personalizados para tareas repetitivas.
- Integración con muchas herramientas y servicios.

<img
  v-click
  class=" -bottom-1 -left-7 "
  src="https://docs.github.com/assets/cb-25535/mw-1440/images/help/actions/overview-actions-simple.webp"
  alt=""
/>

---
layout: image-right
backgroundSize: contain
image: https://img.freepik.com/vector-gratis/ilustracion-colorida-mujer-programadora-haciendo-su-trabajo_23-2148280705.jpg
---

# ¿Qué son GitHub Pages?

- Servicio de alojamiento de sitios web estáticos directamente desde GitHub.
- Ideal para sitios personales, blogs y documentación de proyectos.
- Fácil configuración y despliegue.

<!--
 GitHub Pages es una forma sencilla de publicar nuestro sitio web sin necesidad de un servidor dedicado.
-->

---
layout: image-right
image: https://github.com/images/modules/site/actions/fp24/features-river-breakout.webp
backgroundSize: contain
---

# Creando un workflow de GitHub Actions para desplegar en GitHub Pages

<v-clicks>

- Crear un archivo .github/workflows/main.yml en tu repositorio.
- Definir los pasos del workflow:
  - Checkout del código
  - Instalar dependencias
  - Construir el sitio estático
  - Desplegar en la rama gh-pages

</v-clicks>




<!-- Demuestra un ejemplo sencillo de un workflow de GitHub Actions que se ejecuta cada vez que se empuja un cambio al repositorio principal. -->

<!-- Footer -->

[Leer más](https://docs.github.com/es/actions)

<!-- Inline style -->


---
level: 2
---

# Ventajas de utilizar GitHub Actions y GitHub Pages
<v-clicks>

- Automatización de tareas repetitivas.
- Mayor eficiencia en el desarrollo.
- Colaboración más fácil.
- Despliegues más rápidos y confiables.
- Integración con otras herramientas.

</v-clicks>
---

# Desventajas de GitHub Actions

<v-clicks>

- Curva de aprendizaje
- Costos
- Dependencia de GitHub

<p></p>

# Desventajas de GitHub Pages

- Rendimiento
- Dependencia de GitHub

</v-clicks>

<!--
Curva de aprendizaje: Puede requerir tiempo para dominar la sintaxis de YAML y los conceptos de workflows.
Costos: Para proyectos grandes o con muchos workflows, los minutos de ejecución pueden generar costos.
Dependencia de GitHub: Estás atado al ecosistema de GitHub.

- **Rendimiento:** Puede no ser la mejor opción para sitios web con mucho tráfico o que requieran un alto rendimiento.
- **Dependencia de GitHub:** Al igual que con GitHub Actions, estás limitado al ecosistema de GitHub.
-->

---
class: px-20
---

# Casos de Uso de GitHub Actions

- Integración continua y despliegue continuo (CI/CD)
- Pruebas automatizadas
- Linter y formateadores
- Creación de releases
- Depliegue en múltiples entornos 


<img border="rounded" src="https://github.com/images/modules/site/actions/fp24/hero.webp" alt="">

<!--
Integración continua y despliegue continuo (CI/CD): Automatizar la construcción, prueba y despliegue de aplicaciones.
Pruebas automatizadas: Ejecutar pruebas unitarias, de integración y de extremo a extremo.
Linter y formateadores: Asegurar la calidad del código.
Creación de releases: Automatizar la creación de releases y la generación de notas de cambio.
Depliegue en múltiples entornos: Desplegar en diferentes entornos (desarrollo, staging, producción).
-->

---

# Casos de Uso de GitHub Pages

- Sitios web estáticos
- Documentación de API
- Prototipos

<img border="rounded" src="https://pages.github.com/images/slideshow/facebookdesign.png" alt="">

---
layout: center
class: text-center
---

# Notas

- Presentación Realizada con slidev.

[Documentation](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/resources/showcases)

<PoweredBySlidev mt-10 />
