## Decisiones semánticas
 
**`<html lang="es">`** — El `lang` le dice a los lectores de pantalla en qué idioma está el contenido. Sin esto, pueden pronunciar mal las palabras.
 
**`<meta charset="UTF-8">`** — Necesario para que aparezcan bien las tildes y la ñ. Sin esto, se rompen los caracteres especiales.
 
**`<meta name="viewport">`** — Para que la página no se vea diminuta en el celular.
 
**`<header>`** — Agrupa el nombre y la frase del autor. Se prefirió sobre `<div>` porque tiene significado real: es la cabecera de la página.
 
**`<h1>`** — Solo hay uno, y es el nombre. Es el título más importante del documento.
 
**`<time datetime="2026-03-17">`** — La fecha en texto la entienden las personas; el atributo `datetime` la entienden las máquinas. Usar los dos es la combinación correcta.
 
**`<main>`** — Marca dónde empieza el contenido que importa. Los lectores de pantalla pueden saltar directo aquí.
 
**`<section>`** — Se usaron dos porque el contenido está dividido en dos temas distintos: quién soy, y qué hago. Cada una tiene su `<h2>`, que es lo que las hace secciones válidas.
 
**`<h2>` y `<h3>`** — Se respeta la jerarquía: `<h2>` para el tema de la sección, `<h3>` para los subtemas dentro. Saltar niveles confunde a los lectores de pantalla.
 
**`<strong>`** — Se usó donde la palabra tiene peso real en el texto ("desarrollador web", "CSS"), no para poner negrita decorativa.
 
**`<em>`** — Marca "Ingeniería de Sistemas" con énfasis, como si al leerlo en voz alta le dieras una pequeña inflexión.
 
**`<ul>` y `<li>`** — Las habilidades y pasatiempos no tienen orden de importancia, así que `<ul>` es lo correcto. `<ol>` sería para rankings o pasos.
 
**`<footer>`** — Cierra el documento con los datos de contacto y el año. Más descriptivo que un `<div>`.
 
**`<address>`** — Es la etiqueta específica de HTML para información de contacto del autor. Es exactamente lo que necesitábamos.
 
**`<a href="mailto:...">`** — El esquema `mailto:` abre el cliente de correo al hacer clic, lo que hace la página más funcional sin JavaScript.
 