# Mejora de Accesibilidad en Elementos de Bootstrap con Atributos WAI-ARIA

## Descripción
Este proyecto tiene como objetivo mejorar la accesibilidad de elementos comunes de Bootstrap utilizando los principios de WAI-ARIA.

## Elementos Seleccionados y Mejoras Implementadas

### 1. Botón
- **Atributo añadido:** `aria-pressed`
- **Propósito:** Indica el estado presionado del botón, mejorando la interacción para usuarios de lectores de pantalla.

### 2. Modal
- **Atributos añadidos:** `role="dialog"`, `aria-labelledby`, `aria-describedby`
- **Propósito:** Define el propósito del modal y mejora la navegación proporcionando contexto adicional.

### 3. Menú desplegable
- **Atributos añadidos:** `role="menu"`, `role="menuitem"`, `aria-expanded`, `aria-haspopup`
- **Propósito:** Define roles claros para los elementos del menú y comunica estados dinámicos.

### 4. Alerta
- **Atributo añadido:** `aria-live="polite"`
- **Propósito:** Asegura que el contenido de la alerta sea anunciado de forma apropiada por los lectores de pantalla.

### 5. Pestañas
- **Atributos añadidos:** `role="tablist"`, `role="tab"`, `aria-selected`, `tabindex`
- **Propósito:** Mejora la navegación y la percepción de las pestañas activas para usuarios de teclado y lectores de pantalla.

