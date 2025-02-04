# holamundo-pyside6

## Instalación de Python3

Para instalar Python3 en tu sistema, sigue estos pasos:

### En Windows:
1. Descarga el instalador desde la [página oficial de Python](https://www.python.org/downloads/).
2. Ejecuta el instalador y marca la opción **Add Python to PATH**.
3. Haz clic en **Install Now** y sigue las instrucciones.
4. Verifica la instalación ejecutando en la terminal:
   ```sh
   python --version
   ```

2. Verifica la instalación con:
   ```sh
   python3 --version
   ```

### En Linux (Debian/Ubuntu):
1. Abre la terminal y ejecuta:
   ```sh
   sudo apt update && sudo apt install python3
   ```
2. Verifica la instalación:
   ```sh
   python3 --version
   ```

---

## Instalación y activación de pip

`pip` es el gestor de paquetes de Python y suele venir preinstalado. Para asegurarte de que está instalado:

1. Verifica si `pip` está instalado ejecutando:
   ```sh
   python3 -m pip --version
   ```
2. Si no está instalado, instálalo con:
   ```sh
   python3 -m ensurepip --default-pip
   ```
3. Para actualizar `pip`, usa:
   ```sh
   python3 -m pip install --upgrade pip
   ```

---

## Creación y Activación de Entorno Virtual

Para aislar dependencias, se recomienda usar un entorno virtual:

1. Crea un entorno virtual ejecutando:
   ```sh
   python3 -m venv mi_entorno
   ```
2. Activa el entorno virtual:
   - En Windows:
     ```sh
     mi_entorno\Scripts\activate
     ```
   - En macOS/Linux:
     ```sh
     source mi_entorno/bin/activate
     ```
3. Para desactivar el entorno virtual:
   ```sh
   deactivate
   ```

---

## Instalación de dependencias

Podemos instalar frameworks de Python con:

```sh
pip install nombre_de_la_dependencia
```

## Ejecución de la aplicación

Para ejecutar una aplicación Python:

```sh
python3 app.py
```
  

