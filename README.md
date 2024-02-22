# Para crear un entorno virtual: 
```bash
uv venv  # Create a virtual environment at .venv.
```

# Para activar el entorno virtual: 
```bash
.venv\Scripts\activate
```
s
# Para instalar un paquete en el entorno virtual: 
```bash
uv pip install flask                # Install Flask.
uv pip install -r requirements.txt  # Install from a requirements.txt file.
uv pip install -e .                 # Install the current project in editable mode.
uv pip install "package @ ."        # Install the current project from disk
uv pip install "flask[dotenv]"      # Install Flask with "dotenv" extra.
```

# Actualizar un package editable `-e`:
```bash
uv pip install -e <flet-easy> update                 # Install the current project in editable mode.
```

# Actualizar dependencias `-r`:
```bash
uv pip install -r pyproject.toml update            # Install the current project in editable mode.
```
