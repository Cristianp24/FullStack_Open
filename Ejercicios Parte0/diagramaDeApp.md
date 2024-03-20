//aca va a ir el ejercicio 0.5 del curso.

graph TD;
    A[Usuario accede a la SPA] --> B{Carga la aplicación};
    B -->|Sí| C{Se muestra la página principal};
    C --> D{Interacción del usuario};
    D -->|Guardar nota| E{Petición al servidor};
    E --> F{Actualización de la nota};
    F --> G{Refresco de la interfaz};
    D -->|Ver detalles de la nota| H{Petición al servidor};
    H --> I{Recuperación de detalles de la nota};
    I --> J{Visualización de detalles};
    D -->|Eliminar nota| K{Petición al servidor};
    K --> L{Eliminación de la nota};
    L --> M{Actualización de la interfaz};
    C --> N{Navegación entre vistas};
    N --> O{Carga de la vista correspondiente};
    O --> P{Interacción del usuario};
