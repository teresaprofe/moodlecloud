# Tarea 3.1. MoodleCloud

## Introducción

**Moodle** es una aplicación web para la creación de cursos virtuales basados en Internet. Fue diseñada por Martin Dougiamas, de Perth (Australia Occidental), con base en las ideas del constructivismo pedagógico, según las cuales el conocimiento se construye en la mente del estudiante en lugar de transmitirse sin cambios desde libros o enseñanzas, y en el aprendizaje colaborativo.

La palabra *Moodle* es el acrónimo en inglés de *Modular Object-Oriented Dynamic Learning Environment* (Entorno de Aprendizaje Dinámico Modular Orientado a Objetos). También es un verbo anglosajón que describe el proceso de dar vueltas a algo con calma, haciendo las cosas como se vienen a la mente, una actividad amena que suele llevar a la comprensión y, finalmente, a la creatividad.

En esta práctica trabajaremos con **MoodleCloud**, la versión de Moodle alojada y mantenida por Moodle HQ, que permite usar la herramienta sin instalarla. Solo hay que darse de alta en el **plan de prueba (trial) de 28 días**, que no requiere tarjeta de crédito.

> **Importante:** el periodo de prueba dura 28 días y no existe ningún plan gratuito permanente. Cuando termine, el sitio dejará de estar disponible salvo que se contrate un plan de pago. Haz una **copia de seguridad** del curso antes de que expire (Bloque 5) y termina la práctica con margen.

## Objetivos

1. Aprender a usar la herramienta Moodle una vez instalada.
2. Conocer las funcionalidades principales de la plataforma.
3. Convertirnos en administradores de la herramienta.
4. Conocer las diferencias entre un Moodle propio (autoalojado) y un Moodle en la nube (SaaS).

## Limitaciones de MoodleCloud que debes conocer

| Aspecto | Qué ocurre en MoodleCloud |
| --- | --- |
| Duración de la prueba | 28 días, sin tarjeta de crédito |
| Usuarios | El plan Starter (y su prueba) admite hasta **50 usuarios**. Tenlo en cuenta en la carga masiva del Bloque 3 |
| Plugins y temas de terceros | **No se pueden instalar** en ningún plan estándar; solo hay un conjunto limitado de plugins preinstalados |
| Dominio propio | Disponible solo en planes de pago (añadido en Medium, incluido en Standard). En la prueba se usa una dirección del tipo `tunombre.moodlecloud.com` |
| Videoconferencia | BigBlueButton integrado; en la prueba, las grabaciones se conservan 7 días |

## Normas de presentación

En cada apartado debes mostrar una **captura de pantalla** de lo realizado y añadir un comentario breve explicando qué has hecho o qué has observado. Cuida la presentación del documento.

> **Privacidad:** en las capturas, oculta (difumina) contraseñas y datos personales de terceros que no sean necesarios. No uses datos reales de otras personas en usuarios de prueba, salvo los que pide expresamente el enunciado.

## Bloque 1: Preparando el curso

1. **Alta en MoodleCloud.** Regístrate en MoodleCloud con el plan de prueba (*Start Trial*) y elige un **nombre de sitio propio** (por ejemplo, `tunombre-practica`). Anota la fecha de alta y la fecha en que expira la prueba. Indica en un comentario la **versión de Moodle** que ejecuta tu sitio (*Administración del sitio > General > Notificaciones*).
2. **Categorías.** Crea la siguiente estructura en *Administración del sitio > Cursos > Gestionar cursos y categorías*:
   - MISCELÁNEA
   - FP
     - SMR:
        - 1º SMR
        - 2º SMR
     - DAW
         -1º DAW
         -2º DAW
3. **Cursos.** Crea los siguientes cursos:
   1. **Test**, dentro de la categoría *Miscelánea*.
   2. **Comenzando con Moodle by \[Tu nombre\]**. Debe ser una **copia** del curso que aparece por defecto, *Starting with Moodle*, con todas sus secciones y recursos. Puedes usar la opción *Copiar curso* o hacer una copia de seguridad y restaurarla con otro nombre.

A partir de ahora trabajaremos con el curso **Comenzando con Moodle by \[Tu nombre\]**.

4. **Secciones.** Cambia el nombre de las secciones:
   - *Topic 1: Course activities and resources* → **Tema 1**
   - *Topic 2: Further learning* → **Tema 2**
5. **Nueva sección.** Añade una sección llamada **Tema 3**.
6. **Libro.** Cambia el nombre del libro del Tema 1 a **Aprendiendo Moodle**.
7. **Capítulos del libro.** El libro debe tener estos 3 capítulos, con su contenido correspondiente:
   1. Acerca de Moodle
   2. Qué es Moodle
   3. Ventajas de Moodle
8. **Cuestionario.** Cambia el nombre del cuestionario *Quiz* por **Test**. Modifica las 3 preguntas existentes y añade 2 más. Todas deben estar relacionadas con Moodle.
9. **Área de texto y medios.** Cambia el enlace del vídeo por uno **en español**, modifica el texto y añade algún comentario tuyo.
10. **Foro.** Cambia el nombre del *Forum* a **Foro** y añade tres temas de discusión: *Dudas*, *Sugerencias* y *Avisos*.
11. **Videoconferencia.** Cambia el nombre del recurso *This is a video conferencing room* a **Sala de conferencias**. Entra en la sala (el navegador te pedirá permiso para usar micrófono y cámara) y describe qué ocurre y qué opciones ofrece.
12. **Tarea.** Añade una tarea llamada **Tarea 5.1. MoodleCloud**, como si fuera esta misma tarea:
    - Adjunta un archivo PDF con el enunciado.
    - En *Tipos de archivo aceptados* permite **solo PDF**.
    - Calificación: tipo *Puntuación*, máximo **10**.
13. **Nuevo recurso o actividad.** Añade uno de los disponibles en el selector *Añadir una actividad o un recurso* que **no se haya usado antes** (por ejemplo, Glosario, Wiki, Lección, Consulta, Taller, H5P…) y explica con tus palabras para qué sirve y en qué situación docente lo usarías.

## Bloque 2: Apariencia

Entra en *Administración del sitio > Apariencia > Temas*.

1. ¿Cómo se llama el tema que está usando tu Moodle?
2. ¿Puedes instalar otro tema de terceros? Razona la respuesta teniendo en cuenta las limitaciones de MoodleCloud indicadas arriba.
3. Personaliza el tema actual con las opciones que permita MoodleCloud: cambia al menos el **logotipo** o el **color de marca**, y muestra el antes y el después.
4. Para la siguiente práctica, investiga qué temas existen en el directorio oficial de Moodle y cuáles serían útiles en un centro educativo.

## Bloque 3: Matriculación

Una vez preparado el curso, matricula al alumnado.

1. En *Administración del sitio > Usuarios > Añadir un nuevo usuario*, crea manualmente a tu compañero/a de la izquierda. Después matricúlalo/a en **Comenzando con Moodle by \[Tu nombre\]**.
2. Matricula también a la profesora:
   - Usuario: Teresa Profesora
   - Correo: taloagu305@g.educaand.es
   - Asigna un rol adecuado (por ejemplo, *Profesor* o *Profesor sin permiso de edición*) y explica por qué lo has elegido.
3. Realiza una **carga masiva** de usuarios desde el archivo CSV proporcionado, en *Administración del sitio > Usuarios > Subir usuarios*. Comprueba antes que el archivo está en codificación **UTF-8** y que el número total de usuarios no supera el límite de tu plan (50). Muestra la pantalla de previsualización y el resultado.
4. Una vez cargados, **matricula a los 10 primeros usuarios** en tu curso, y muestra la lista de participantes.

## Bloque 4: Plugins

En MoodleCloud **no es posible instalar plugins de terceros**, por lo que este bloque se centra en conocer los que ya incluye el sitio.

1. En *Administración del sitio > Extensiones > Vista general de plugins*, muestra los plugins instalados por defecto.
2. Localiza un plugin de tipo *Actividad* y otro de tipo *Bloque*, y describe para qué sirve cada uno.
3. Activa, desactiva o configura uno de los plugins preinstalados (por ejemplo, desde *Extensiones > Módulos de actividad > Gestionar actividades*) y muestra el efecto en el curso.
4. Investiga en el directorio oficial de plugins (moodle.org/plugins) uno que te parezca interesante para un centro educativo. Explica qué hace y por qué **no** podrías instalarlo en MoodleCloud. ¿En qué tipo de instalación de Moodle sí podrías hacerlo?

## Bloque 5: Copia de seguridad

1. Realiza una **copia de seguridad** de tu curso (desde el curso, *Más > Reutilización de curso > Copia de seguridad*). Descarga el fichero `.mbz`, súbelo a tu unidad de almacenamiento (Drive) y compártelo con tu compañero/a de la derecha. Al hacer la copia, desmarca la opción de incluir datos de usuarios si no es necesaria.
2. **Restaura** el curso de tu compañero/a en tu Moodle. Comprueba que se han cargado todos los elementos (secciones, libro, test, foro, tarea…) y muestra el resultado.
3. Intenta matricular a tu compañero/a de la derecha en el curso restaurado. ¿Qué necesitas hacer antes de poder matricularlo? Explica el motivo.

## Conclusión y valoración personal

Explica **con tus palabras** qué has aprendido y valora el trabajo realizado. Incluye, además:

- Dos ventajas y dos inconvenientes de usar MoodleCloud frente a instalar Moodle en tu propio servidor.
- Qué harías para conservar tu trabajo cuando termine el periodo de prueba.

## Entrega

La entrega se realizará en **un único archivo PDF** que contenga:

- Portada con tu nombre y el título de la práctica.
- Cada apartado con su enunciado, su captura de pantalla y tu explicación.
- La conclusión y valoración personal.



