# Instalación de Python

## 1: Descarga
* Desde la **[Web oficial de Python](https://www.python.org/)** en la sección **Descargas >> Windows** identificar la version y dercargar el instalador.

![](./IMG/IMG_01.png)


## 2: Instalación
* Ejecutar el instalador y marcar las dos opciones:
    * *Use admin privileges when installing py.exe*
    * *Add python.exe al PATH*

![](./IMG/IMG_02.png)

* Comprobar instalación de Python y PIP (gestor de paquetes para Python):
    * Abrir el Símbolo del sistema: *Ctrl+R* o buscar CMD y ejecutar.
        ```python
        python --version
        ```
    * Para verificar las instalación de PIP ejecutar.
        ```python
        pip --version
        ```


## 3: Configuración del PATH

* En el explorador de window buscar **varibales de entorno del sistema**.
    * Verificar que dentro de **path** exista la ruta ```C:\Users\...\AppData\Local\Programs\Python\Python311\Scripts\```.

    * En caso no exista la ruta. Con *Ctrl+R* buscar **AppData** y seguir  la ruta **Local>>Programs>>Python>>Python311>>Scrits**. y obtener la ruta de la carpeta y agregar dentro de **path** *(entorno de variables del sistema)*
