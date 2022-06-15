# Práctica 2. Máquina Virtual (VM) para programar desde ML Azure
## Creación del Notebook
En [Microsoft Azure Machine Learning](https://ml.azure.com/home) creamos un área de trabajo. Al igual que en las otras instancias necesitaremos
- Nombre para nuestra área de trabajo: sesiones_ia
- Suscripción: Azure for Students
- Grupo de recursos: en este caso creamos el grupo de recursos sesionesia
- Región: East US2

![sesionia1](imagenes\sesionia1.png)

En nuestra área de trabajo, en la barra de la izquierda buscamos "Proceso" y en Instancias de proceso seleccionamos "+ Nuevo".

![sesionia2](imagenes\sesionia2.png)

Configuramos el proceso:
- Nombre del proceso: debe ser único, para este caso será "notebook-python"
- Tipo de máquina virtual: CPU
- Tamaño de la máquina virtual: Standard_DS11_v2
Y seleccionamos crear.

![sesionia3](imagenes\sesionoa3.png)

Ahora en el menú de la izquierda buscamos los Notebooks, en es símbolo de "+" seleccionamos "Crear archivo".

![sesionia4](imagenes\sesionia4.png)

Elegimos un nombre para el archivo, holamundo.ipynb, y un tipo de acrchivo, Cuaderno(*.ipynb), y presionamos "Crear"
.ipynb es importante en el nombre ya que especificamos que programaremos en Python.

![sesionia5](imagenes\sesionia5.png)

--------------------
## Programación en el Notebook
Para programar simplemente lo hacemos de manera normal, para correr el programa lo hacemos desplegando el menú que se encuentra junto a la flecha. Los resultados se muestran en la página inferior.

![sesionia6](imagenes\sesionia6.png)

Podemos seleccionar "Editar en VS Code (versión preliminar)", con ello se abrirá VS Code y los resultados de nuestra programación los observaremos en Azure Machine Learning.

![sesionia7](imagenes\sesionia7.png)

----------------------
## Apagar la Máquina Virtual
La VM consume muchos recursos, por lo que será necesario apagarla o eliminara.
Para apagar la VM, en instancias del proceso seleccionamos el Notebook y presionamos "Detener", quedando la máquina inhabilitada.

![sesionia8](imagenes\sesionia8.png)

Para volver a usar la VM, seleccionamos el Notebook y presionamos "Iniciar".

![sesionia9](imagenes\sesionia9.png)

--------------------------
### Extra
En Azure Portal podemos observar los recursos que se han creado:
- Azure Machine Learning
- Applications Insights
- Cuenta de almacenamiento
- Almacén de claves

![sesionia10](imagenes\sesionia10.png)