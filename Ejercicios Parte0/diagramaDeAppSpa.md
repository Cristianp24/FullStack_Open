// aca va a ir el ejercicio 0.6 del curso.


graph TD;
    A[Usuario crea una nueva nota] --> B{Guarda la nota};
    B -->|Sí| C{Validación de campos};
    C -->|Sí| D{Petición al servidor};
    D --> E{Procesar datos};
    E --> F{Actualizar lista de notas};
    F --> G{Mostrar mensaje de éxito};
    B -->|No| H{Mostrar mensaje de error};
