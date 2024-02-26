Para ejecutar el proyecto se deben de seguir los siguientes pasos:

1. Crear un entorno virtual

   ```bash
   python -m venv venv
   ```

2. Activar el entorno virtual

Si se está en un sistema operativo basado en Windows se debe de ejecutar el siguiente comando:

```bash
.\venv\Scripts\activate
```

Si se está en un sistema operativo basado en Unix (Linux o MAC) se debe de ejecutar el siguiente comando:

```bash
source venv/bin/activate
```

3. Instalar las dependencias

   ```bash
   pip install -r requirements.txt
   ```

4. Ejecutar el proyecto
   ```bash
   jupyter notebook
   ```
