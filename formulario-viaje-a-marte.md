# 🚀 Proyecto: Reclutamiento "Misión Marte 2026"

## Contexto

La agencia espacial **Interstellar** busca colonos para la primera base en Marte. Tu misión es construir el formulario de postulación oficial. Debe ser técnico, validado y tener una apariencia futurista.

## 🛠️ Requisitos Técnicos (Fase HTML)

Deben crear un archivo `index.html` estructurado con `fieldset` y `legend` para organizar la información.

### 1. Sección: Identidad Terrestre

- **Nombre completo**: Campo de texto obligatorio.
- **Email**: Validación nativa de correo (`type="email"`).
- **Fecha de Nacimiento**: Selector de fecha (`type="date"`). *Dato: El recluta debe ser mayor de edad.*
- **Número de ID de Recluta**: Usar un campo de tipo numérico (`type="number"`) que sea obligatorio.

### 2. Sección: Perfil de Vuelo

- **Rol en la Misión**: Un menú desplegable (`select`) con las opciones:
  - Ingeniero de Oxígeno
  - Biólogo de Invernadero
  - Piloto de Naves de Carga

- **Habilidades Especiales**: Una lista de casillas de verificación (`checkbox`) que incluya:
  - Reparación de Robots
  - Primeros Auxilios
  - Cultivo Hidropónico
  - Telecomunicaciones

### 3. Sección: Motivación y Seguridad

- **Carta de Motivos**: Un área de texto (`textarea`) de al menos 4 filas donde expliquen por qué quieren abandonar la Tierra.
- **Clave de Acceso**: Campo de tipo `password` con un mínimo de 10 caracteres (`minlength="10"`).
- **Botón de Envío**: Un botón que diga "Iniciar Lanzamiento".

> ⚠️ **Regla de Oro**: Todos los campos deben tener un `label` vinculado correctamente mediante los atributos `id` y `for`.

## 🤖 El Desafío del Prompt (Fase Estilo)

Sin modificar el código HTML que escribieron, deben pedirle a una Inteligencia Artificial (ChatGPT, Gemini, etc.) que genere el CSS para su formulario.

### Consigna:

1. Redacten su propio prompt.
2. El diseño debe ser temático (Sci-fi, futurista, estilo NASA o Cyberpunk).
3. **Restricción**: No pueden cambiar las etiquetas HTML, solo pueden copiar el CSS resultante en un archivo `style.css` o dentro de una etiqueta `<style>`.

## 🛰️ Lanzamiento y Control de Calidad

### Despliegue

Guarden su carpeta y arrástrenla a Netlify para obtener un link público.

### Revisión (Peer Review)

Intercambien su link con otra pareja y completen este checklist sobre el formulario ajeno:

| Ítem a revisar | ¿Cumple? (Sí/No) |
|---|---|
| Al hacer click en el texto del Label, ¿se activa el Input? | |
| ¿El campo de Email impide enviar textos que no sean correos? | |
| ¿La contraseña impide el envío si tiene menos de 10 caracteres? | |
| ¿El formulario es legible en dispositivos móviles? | |
| ¿El diseño visual es coherente con la temática espacial? | |

### Entrega

Compartan el link de Netlify por WhatsApp. ¡Buen viaje! 🚀