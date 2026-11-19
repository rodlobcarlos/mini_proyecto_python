# mini_proyecto_python

Script en Python diseñado para localizar y ejecutar un script de Bash externo (`script.sh`), capturando tanto su salida estándar como posibles errores para extraer la información generada.

## 📁 Estructura del proyecto

```text
├── mini_proyecto_bash/      # Repositorio hermano requerido
│   └── script.sh            # Script de Bash objetivo
└── mini_proyecto_python/
    ├── README.md
    └── scritp.py            # Script principal en Python
    └── .gitignore
```

📋 Requisitos previos

- Python 3.x (utiliza las librerías estándar subprocess y pathlib, por lo que no requiere instalar dependencias externas).
- Entorno Bash (Linux, macOS o WSL si se ejecuta desde Windows).
- Tener el directorio mini_proyecto_bash con el archivo script.sh ubicado al mismo nivel que la carpeta de este repositorio.

🚀 Uso

1. Clona este repositorio en el mismo directorio padre donde se encuentre mini_proyecto_bash:
   ```bash
   git clone [https://github.com/rodlobcarlos/mini_proyecto_python.git](https://github.com/rodlobcarlos/mini_proyecto_python.git)
   cd mini_proyecto_python
   ```
   
2. Ejecuta el script de Python:
   ```bash
   python3 scritp.py
   ```

3. El programa mostrará por consola:

- Los errores del script de Bash (si los hubiera).
- La salida estándar obtenida tras la ejecución.

--- 

👤 Autor
Carlos Rodríguez Lobato - @rodlobcarlos
