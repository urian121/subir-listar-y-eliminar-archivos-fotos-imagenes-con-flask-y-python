# Configuración del Entorno Virtual y Dependencias

Sigue estos pasos para configurar y ejecutar el proyecto en un entorno virtual con Flask.

### Paso 1: Crear el entorno virtual
```bash
python3 -m venv env
```

### Paso 2: Activar el entorno virtual
- En **Windows**:
  ```bash
  .\env\Scripts\activate
  ```
- En **macOS/Linux**:
  ```bash
  source env/bin/activate
  ```

### Paso 3: Instalar Flask y otras dependencias
Dentro del entorno virtual, instala Flask:
```bash
pip install flask
```

### Crear o Actualizar `requirements.txt`
Para guardar las dependencias actuales del proyecto en `requirements.txt`, usa:
```bash
pip freeze > requirements.txt
```

### Instalar Dependencias desde `requirements.txt`
Para instalar todas las dependencias necesarias desde `requirements.txt`, ejecuta:
```bash
pip install -r requirements.txt
```

### Actualizar pip
Para asegurarte de que `pip` está en su última versión:
```bash
python -m pip install --upgrade pip
```

### Desactivar el Entorno Virtual
Cuando termines de trabajar, puedes desactivar el entorno virtual con:
```bash
deactivate
```
