# Registro de Prompts Utilización IA: Claude

## Contexto general
Sesión de programación asistida entre un estudiante principiante y Claude.  
Proyecto: **Gestor de Tareas UCT** (HTML + CSS + JavaScript).

---

## Prompts utilizados

### Entrega del HTML y solicitud del JavaScript
**Prompt:**
> *[Código HTML del Gestor de Tareas]* + "verifica que el archivo javascript basado en este código cumpla con las siguientes funcionalidades"

**Uso:** Prompt de generación de código con contexto adjunto. El usuario proporcionó el HTML como base y solicitó que el JavaScript fuera coherente con su estructura (IDs, formulario, secciones).
Se complementó con una segunda ronda de preguntas para definir las funcionalidades exactas.

---

### Definición de funcionalidades del JavaScript
**Prompt:**
> 1. Agregar tarea: Desde formulario → pendientes  
> 2. Cambiar estado: Botones en cada tarjeta  
> 3. Eliminar tarea: Botón eliminar en tarjeta  
> 4. Contadores: Actualizar automáticamente  
> 5. Validación: Campos no vacíos

**Uso:** Prompt de verificación de requisitos. Lista numerada y clara que definió exactamente qué debía hacer el archivo `script.js`. Permitió generar código funcional sin ambigüedades.

---

### Entrega del HTML actualizado y solicitud del CSS
**Prompt:**
> *[Código HTML actualizado]* + "genera un codigo CSS para centrar en columnas y los valores; 'pendientes', 'en-progreso' y 'completadas'"

**Uso:** Prompt de generación de estilos con contexto adjunto. El usuario entregó una nueva versión del HTML (con cambios en etiquetas y estructura) y pidió CSS específico para el layout de columnas.
Claude generó `style.css` y `responsive.css` completos.

---

### Solicitud de simplificación del CSS
**Prompt:**
> "Haz el código mas simple, solamente centrando los valores que ya te di"

**Uso:** Prompt de refinamiento o reducción. Indicó que la respuesta anterior era demasiado extensa y que solo se necesitaba lo esencial: centrar las 3 columnas.
Resultó en un CSS de 10 líneas enfocado exclusivamente en `flexbox`.

---

### Solicitud de este documento
**Prompt:**
> "Redacta un documento .md que contenga los prompts utilizados en esta sesion y de que forma se utilizaron"

**Uso:** Prompt de documentación. Pidió un resumen estructurado de todos los prompts de la sesión, incluyendo su propósito y efecto. 
Útil para reflexionar sobre cómo se comunican instrucciones a una IA de forma efectiva.

---

## Observaciones sobre el uso de prompts

- Reflexión sobre el uso de prompts o inteligencia artificial.
- En un comienzo no se contemplaba la utilización de ningún tipo de IA pero debido a ciertas complicaciones con JS se llego a la necesidad de usarla.
- Fue de gran ayuda para JS.
- Aunque el tiempo invertido antes de usar la IA en js tuvo como consecuencia descuidar los demás aspectos del proyecto.
- Se considerara el uso de la IA para optimizar recursos en una siguiente ocasión.
