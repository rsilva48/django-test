# ars-pgsweb

Proyecto de Sitio Web para cliente usando Python como backend con el framework Django

# Configuración de entorno y dependencias

## Instalación de Python 3.12.1

### Windows:

Descargar e instalar la [versión 3.12.1 de Python](https://www.python.org/downloads/release/python-3121/):

- [Windows 64-bit](https://www.python.org/ftp/python/3.12.1/python-3.12.1-amd64.exe)

**Nota:** Colocar la opción de añadir Python al Path (Variables de entorno) antes de empezar la instalación.

### Linux:

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

## Creación de entorno virtual

### Linux:

```bash
sudo pip3.12 install virtualenv
virtualenv venv
```

### Windows:

```cmd
python -m venv venv
```

## Activación de entorno virtual

### Linux:

```bash
source venv/bin/activate
```

### Windows (CMD):

```cmd
venv\Scripts\activate
```

### Windows (PowerShell)

```powershell
.\venv\Scripts\Activate
```

## Desactivación de entorno virtual

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
