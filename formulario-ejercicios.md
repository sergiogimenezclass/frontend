# Guía de Ejercicios: Formularios HTML (Nivel Inicial)

10 ejercicios rápidos

---

## 1. El Foco Automático (Label + ID)

**Objetivo:** Vincular etiquetas con campos.

**Consigna:** Armá un campo de texto para "Nombre de Usuario". Hacé que, si el usuario clickea en la palabra "Nombre", el cursor se pose automáticamente dentro del cuadrito de texto.

---

## 2. Validación de Correo (Type Email)

**Objetivo:** Usar validaciones nativas del navegador.

**Consigna:** Creá un input que solo acepte correos electrónicos. Agregale el atributo para que sea obligatorio (required) y fijate qué pasa si intentás enviar el formulario vacío o con un texto cualquiera.

---

## 3. Contraseña Segura (Minlength)

**Objetivo:** Restringir la longitud de entrada.

**Consigna:** Armá un campo de contraseña. Configuralo para que el navegador no te deje enviar el formulario si la clave tiene menos de 8 caracteres.

---

## 4. Elegí tu Fecha (Type Date)

**Objetivo:** Usar el calendario nativo del navegador.

**Consigna:** Creá un campo para que el usuario elija su "Fecha de Nacimiento". Usá el type correcto para que se abra un calendario al hacer click y no sea un simple texto.

---

## 5. Lista de Habilidades (Checkboxes)

**Objetivo:** Entender la selección múltiple.

**Consigna:** Hacé una lista de tres casillas de verificación (checkbox) con lenguajes: "HTML", "CSS" y "JavaScript". El usuario tiene que poder marcar todos los que quiera.

---

## 6. El Área de Comentarios (Textarea)

**Objetivo:** Manejar entradas de texto largas.

**Consigna:** Agregá un campo donde el usuario pueda escribir un mensaje largo. No uses un input común, buscá la etiqueta que permite varias líneas de texto y definí que empiece con 4 filas de alto.

---

## 7. Selector de Provincias (Select)

**Objetivo:** Implementar listas desplegables.

**Consigna:** Armá un menú desplegable (select) que permita elegir entre tres provincias (ej: Buenos Aires, Córdoba, Santa Fe). Agregá una opción inicial que diga "Seleccioná tu provincia" y que no tenga valor.

---

## 8. El Cartelito de Ayuda (Title)

**Objetivo:** Mejorar la UX con tooltips nativos.

**Consigna:** A un campo de "Código Postal", agregale un atributo title que explique: "Debe tener 4 números". Poné el mouse encima sin hacer click y fijate si aparece el cartelito.

---

## 9. Autocompletado Pro (Autocomplete)

**Objetivo:** Ayudar al navegador a sugerir datos.

**Consigna:** Creá un campo para "Correo Electrónico" y otro para "Contraseña actual". Usá el atributo autocomplete con los valores específicos (email y current-password) para que el navegador sepa exactamente qué datos sugerir.

---

## 10. ¿Enviar o No Enviar? (Submit vs Button)

**Objetivo:** Diferenciar el comportamiento de los botones.

**Consigna:** Poné dos etiquetas `<button>` adentro de un formulario. Al primero ponele type="submit" y al segundo type="button". Fijate cuál de los dos recarga la página (envía) y cuál no hace absolutamente nada al clickearlo.