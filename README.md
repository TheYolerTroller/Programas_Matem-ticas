# Programas de Matemáticas
Compilación de programas de matemáticas realizados durante el curso de Matematicas Discretas y Calculo, estudiando en la carrera de Ingeniería en Ciencias de la Computación en la Benemérita Universidad Autónoma de Puebla.


## Puesta en Marcha
El primero de los pasos para poner en marcha los proyectos es clonar el repositorio en tu máquina local descargando el código en formato `.zip`; o si eres un usuario más avanzado, usando `git clone`:

```bash
git clone https://github.com/Rhallyhfk/Programas_Matem-ticas
```

Todos los proyectos desarrollados en python cuentan con un ejecutable dentro del directorio `dist` dentro de su respectiva carpeta, por lo que para correrlos solo es necesario ejecutar el archivo `.exe` correspondiente.

Los códigos fuente se pueden visualizar con cualquier editor de texto o IDE que soporte Python, como Visual Studio Code, PyCharm, entre otros.Ejecución 

### Ejecución a partir del Código Fuente
Para ejecutar los programas, asegúrate de tener [Python](https://www.python.org/downloads/)Python instalado en tu sistema. Luego, clona este repositorio y navega hasta el directorio del programa que deseas ejecutar. Usa el siguiente comando en tu terminal:

```bash
cd ruta/al/directorio/del/programa
python nombre_del_programa.py
```

Ten en cuenta que algunos programas pueden requerir dependencias adicionales. Estas se pueden instalar usando `pip` y el archivo `requirements.txt`

```bash
pip install -r requirements.txt
```

### Ejecución con un Entorno Virtual (recomendado)
Si no deseas instalar las dependencias globalmente, puedes crear un entorno virtual de Python e instalar las dependencias ahí.

Primero, creamos el entorno vitual con una terminal dentro de la carpeta del proyecto:
```bash
python -m venv venv # Crear entorno virtual llamado 'venv'
```
Luego, activamos el entorno virtual:

- En Windows:
  ```powershell
  .\venv\Scripts\activate
  ```
- En macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

Finalmente, instalamos las dependencias necesarias usando el archivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Contribuyentes
<a href="https://github.com/Rhallyhfk/Programas_Matem-ticas/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Rhallyhfk/Programas_Matem-ticas" />
</a>
