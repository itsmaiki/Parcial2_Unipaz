# Modelo de datos del sistema e-VALuación

| Tabla | Descripción | Campos principales |
|--------|--------------|--------------------|
| usuario | Registra información básica de los usuarios | id_usuario, nombre, correo, rol |
| docente | Datos del docente evaluado | id_docente, nombre, programa, área |
| evaluacion | Información de cada formulario aplicado | id_eval, fecha, id_docente |
| pregunta | Contiene las preguntas de la encuesta | id_preg, texto, categoria |
| respuesta | Guarda las respuestas de los estudiantes | id_resp, id_eval, id_preg, valor |
| resultado | Promedios y calificaciones finales | id_result, id_docente, promedio |

Este modelo permite almacenar de forma ordenada los datos de las evaluaciones y facilita la generación de reportes.
