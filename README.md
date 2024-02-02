# ars-pgsweb

Web para cliente usando Python como backend con el framework Django

## Configuración de ambienta virtual

### Instalación de Python 3.12.1 (Windows)

Descargar la [versión 3.12.1 de Python](https://www.python.org/downloads/release/python-3121/):

- [Windows 64-bit](https://www.python.org/ftp/python/3.12.1/python-3.12.1-amd64.exe)

### Instalación de Python 3.12.1 (Linux):

Ejecutar los siguientes comandos:

```bash
sudo apt-get update
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev \
libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev \
xz-utils tk-dev libffi-dev liblzma-dev python3-openssl git
cd /usr/src
sudo wget https://www.python.org/ftp/python/3.12.1/Python-3.12.1.tgz
sudo tar xzf Python-3.12.1.tgz
cd Python-3.12.1
sudo ./configure --enable-optimizations
sudo make altinstall
python3.12 -m pip install --upgrade pip
```

### Creación de entorno virtual Linux

```bash
sudo pip3.12 install virtualenv
virtualenv venv
```

### Creación de entorno virtual Windows

```cmd
python -m venv venv
```

### Activación de entorno virtual en Linux

```bash
source venv/bin/activate
```

### Activación de entorno virtual en Windows (CMD)

```cmd
venv\Scripts\activate
```

### Activación de entorno virtual en Windows (PowerShell)

```powershell
.\venv\Scripts\Activate
```

### Desactivar entorno virtual

```bash
deactivate
```

## Configuración de dependencias

### Instalación de dependencias

```bash
pip install -r requirements.txt
```

### Almacenar listado de dependencias en requirements.txt

```bash
pip freeze > requirements.txt
```
