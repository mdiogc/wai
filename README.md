# Mejoras de Accesibilidad con WAI-ARIA

Este proyecto tiene como objetivo mejorar la accesibilidad de diversos elementos de Bootstrap utilizando los atributos WAI-ARIA. Los atributos WAI-ARIA permiten que los usuarios con discapacidades, que utilizan tecnologías de asistencia (como lectores de pantalla), tengan una mejor experiencia de navegación en la web.

## Elementos Mejorados

Se han mejorado los siguientes cinco elementos de **Bootstrap** con los atributos WAI-ARIA:

1. **Botón**
2. **Menú desplegable**
3. **Alerta**
4. **Pestañas**
5. **Formulario**

### 1. **Botón**
- Se añadió el atributo `aria-pressed="false"` para indicar si el botón está presionado o no. Esto es útil especialmente en botones de alternar estado (toggle buttons).
- Este atributo permite a los usuarios con tecnologías de asistencia saber si el botón ha sido presionado o no.

### 2. **Menú Desplegable**
- Se añadió el atributo `aria-haspopup="true"` al botón del menú para indicar que tiene un submenú.
- También se incluyó `aria-expanded="false"` para reflejar si el menú está abierto o cerrado. Este atributo debería cambiar dinámicamente en aplicaciones más complejas con JavaScript.

### 3. **Alerta**
- Se añadió el atributo `aria-live="polite"` para garantizar que las alertas se anuncien de manera oportuna sin interrumpir otras interacciones importantes.
- Esto es especialmente útil para los usuarios que necesitan ser informados de una alerta sin que se les interrumpa abruptamente.

### 4. **Pestañas**
- Se añadieron los atributos `role="tablist"` y `role="tab"` a las pestañas, indicando su rol dentro de la estructura de la interfaz de usuario.
- Se incluyó `aria-selected="true/false"` para indicar qué pestaña está activa y cuál está inactiva.
- El atributo `tabindex="0"` se añadió a la pestaña activa para permitir su selección mediante teclado.

### 5. **Formulario**
- Se utilizó `aria-describedby="usernameHelp"` y `aria-describedby="passwordHelp"` para proporcionar descripciones adicionales a los campos de entrada, lo que ofrece más contexto a los usuarios sobre los requisitos de cada campo.
- Aunque no se incluyó en el código, el atributo `aria-required="true"` puede ser útil para indicar campos obligatorios, y podría añadirse si fuera necesario.

## Objetivo del Proyecto

El objetivo es mejorar la accesibilidad web en la página, asegurando que los usuarios con discapacidades puedan interactuar mejor con los elementos comunes de la interfaz de usuario proporcionados por **Bootstrap**.

Los cambios realizados proporcionan información adicional para tecnologías de asistencia, lo que ayuda a los usuarios a comprender mejor el propósito de cada elemento y navegar por la página de manera más eficiente.

