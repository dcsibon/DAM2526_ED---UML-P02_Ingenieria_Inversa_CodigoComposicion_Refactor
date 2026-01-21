
# **P03 – Agenda_Composición_Refactor**

## Refactorización guiada por UML, documentación y TODOs

### 1. Objetivo de la práctica

En esta práctica vas a **refactorizar** una aplicación Java de Agenda de contactos (consola) siguiendo un diseño ya definido.

Se te proporciona:

* el **diagrama de clases UML final** (ya terminado),
* **documentación (Javadoc)**,
* y **comentarios TODO** en el código,

y tu trabajo consiste en **implementar las nuevas clases y adaptar el programa** para que funcione con la nueva estructura.

📌 **Importante:**

* **NO tienes que crear UML.**
* **NO tienes que modificar el UML.**
* Tu tarea es **leer el UML + documentación + TODOs** y programar lo que falta como se ha diseñado.

---

### 2. Material proporcionado

En el repositorio encontrarás:

* un **UML final** con la estructura refactorizada,
* clases nuevas (o plantillas) con **TODOs**,
* documentación en el código.

* Además tenéis el código de la práctica anterior que os he subido a Moodle: [DAM2526_ED---UML-P02_Ingenieria_Inversa_CodigoComposicion](https://github.com/dcsibon/DAM2526_ED---UML-P02_Ingenieria_Inversa_CodigoComposicion/tree/main)

---

### 3. Qué debéis hacer

Debéis implementar las clases indicadas en el UML (tenéis ayudas en la documentación y en los TODOs):

* **`Consola`**
  Encapsula la lectura de datos por teclado y la escritura por pantalla.
  Debe incluir métodos para leer texto, leer enteros y validar entradas.

* **`Menu`**
  Se encarga de mostrar el menú principal y leer la opción elegida.
  Debe apoyarse en `Consola` (no debe usar `Scanner` directamente).

* **`GestorAgenda`**
  Implementa las operaciones que el usuario puede ejecutar desde el menú:

Debéis modificar `Main` para:

* crear los objetos necesarios (`Consola`, `Menu`, `Agenda`, `GestorAgenda`),
* ejecutar el bucle principal del programa,
* delegar toda la lógica en las clases anteriores.

---

### 5. Qué se comprobará en clase

En clase revisaremos:

* si el programa funciona correctamente,
* si has seguido el UML entregado,
* si tu código es claro y está bien organizado.

---

### 6. Entrega

Sube al repositorio tu solución con un proyecto de Java que contenga:

* las nuevas clases implementadas,
* `Main` adaptado,
* el proyecto ejecutable.

