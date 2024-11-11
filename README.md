# Introduccion
Esto es un proyecto realizado para la materia Fundamentos de la Ciencia de Datos. Se analizó un DataSet dado y se obtuvieron conclusiones sobre el.. etc.

# Modo de uso
Guia para la lectura y descarga del trabajo.

## Descarga de los archivos necesarios
Se deben descargar los archivos necesarios los cuales están contenido es en el repositorio. Recomendamos estos metodos.

### Utilizando GIT
En este método se utilizará la herramienta GIT para clonar el repositorio en el destino deseado.
> [!IMPORTANT]
> No se incluye la instalación de la herramienta GIT en esta guía, ya que escapa al alcance del trabajo.

Para clonar el repositorio, abre una terminal y ejecuta el siguiente comando:

```
git clone https://github.com/iroumec/TPE-FCD
```
Creación de un entorno virtual

### Realizando una descarga directa desde el repositorio de GitHUB
Para asegurar que las dependencias se instalen correctamente, se recomienda crear un entorno virtual. Desde la terminal, navega a la carpeta del proyecto y ejecuta:


python3 -m venv env
Activación del entorno virtual

En Linux o Mac:
bash
Copiar código
source env/bin/activate
En Windows:
bash
Copiar código
.\env\Scripts\activate
Instalación de dependencias
Con el entorno virtual activo, instala las dependencias del archivo requirements.txt para poder ejecutar la notebook de análisis:

bash
Copiar código
pip install -r requirements.txt
