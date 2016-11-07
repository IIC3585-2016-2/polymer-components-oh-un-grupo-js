# Componentes reusables en Polymer
&lt;mi-radio>, &lt;post-eso> y &lt;post-eso-gen> polymer custom elements

## `<mi-radio>`
Componente de radio que hace stream de música.

*Features*: muestra metadatos del stream de haberlo.

Definición de componente en `mi-radio.html`
Demo en `demo/mi-radio-index.html`


## `<post-eso>`
Componente inspirado en Post-Its. 

*Features*: draggable, resizable, autoresizable text area, re-estilización automática basado en largo de texto (da cuenta de la importancia del recordatorio). Cuenta con custom properties para modificación de estilo de post-esos.

Definición de componente en `post-eso.html`
Demo en `demo/post-eso.html`

## `<post-eso-gen>`
Generador de post-esos.

*Features*: tapear un paper-button para la generación de post-esos. Hereda custom-properties y textlength trigger de `<post-eso>` para encapsularlo totalmente y poder utilizarlos sin necesidad de definir post-esos a parte del `<post-eso-gen>`

Definición de componente en `post-eso-gen.html`
Demo en `demo/post-eso-gen.html`

## Viendo la Aplicación

```
$ polymer serve --open
```
Documentaciones respectivas en `http://localhost:8080/components/<app_folder>/#mi-radio`, `/<app_folder>/#post-eso` y `/<app_folder>/#post-eso-gen`.
