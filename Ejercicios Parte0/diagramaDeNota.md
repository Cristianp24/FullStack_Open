// aqui va a ir el ejercicio 0.4 del curso.

graph TD;

    A[Usuario escribe una nueva nota] --> B{Click en botón "Save"};
    B -->|Sí| C{Validación de campos};
    C -->|Sí| D{Enviar datos al servidor};
    D --> E{Procesar datos};
    E --> F{Actualizar lista de notas};
    F --> G[Mensaje de éxito];
    B -->|No| H{Mostrar mensaje de error};
