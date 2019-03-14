# Taller Introducción a la analítica

En este taller utilizaremos herramientas cloud para realizar análisis y reportes sobre un dataset

## Dataset
El dataset contiene datos sobre camppañas de mercadeo de un banco, realizadas anteriormente, y se puede descargar de este [sitio](http://bml.io/VGoAkz)
La idea es utilizar los datos para analizar las campañas y entender la relación entre el cliente y el resultado de dichas campañas.

## Prerequisitos

* Cuenta en IBM Cloud (Bluemix)
* [Dataset](dataset/customer_analytics.csv)


## Watson Studio

Es el punto central donde crearemos el proyecto, al cual agregaremos el dataset, y el módulo de reportes.

### Crear la instancia de Watson Studio:

En el menú de la izquierda seleccionar Dashboard ->  Create Resource -> AI  -> Watson Studio -> ingresar un nombre ("womenindata studio") -> Plan Lite -> Create y click en Get Started


### Proyecto en Watson Studio

Una vez creada la instancia de Watson Studio, debemos crear un proyecto. Dentro de dicho proyecto estarán asociados los recursos que necesitaremos, en este caso el dataset y el módulo de reportes. 

### Crear nuevo proyecto
Click en New Project -> Business Analytics -> Create Project -> Region: US -> Create

Esto creará por debajo 2 componentes:

* Cloud Object Storage (dataset)
* Cognos (dashboard)

### Adicionar Dataset

Ir a la pestaña Assets y a la derecha dar click en Browse y subir el dataset

![image](https://user-images.githubusercontent.com/41264/54388037-d2e1c580-466a-11e9-88df-4ad8c69edabd.png)

### Adicionar dashboard

En Add to project

![image](https://user-images.githubusercontent.com/41264/54388849-b6df2380-466c-11e9-9520-a17aebfbe97d.png)

Click en Save

Seleccionar infographic y el layout indicado

![image](https://user-images.githubusercontent.com/41264/54389022-235a2280-466d-11e9-83e3-e8093d5040e3.png)

Click en OK

### Definir data source

En el panel de la izquierda, clic en el boton más al lado de "Selected sources"

![image](https://user-images.githubusercontent.com/41264/54389265-ada28680-466d-11e9-886d-6c0ce53bac13.png)

Dentro de data assets, seleccionar el archivo csv

![image](https://user-images.githubusercontent.com/41264/54389360-da569e00-466d-11e9-80df-942ddf3d05e9.png)

Dar clic en el dataset. A continuación se despliegan los campos del dataset.

![image](https://user-images.githubusercontent.com/41264/54389538-4d601480-466e-11e9-8b4f-8f3f80c2e709.png)


### Visualización

Para crear una visualización, tomaremos dos campos como  *job* y *balance*, las seleccionamos con *Control* y las arrastramos al centro del cuadro principal

![image](https://user-images.githubusercontent.com/41264/54390416-6cf83c80-4670-11e9-8cd6-fad5c737d92a.png)



### Editar visualización

Clic en la cruz en la parte superiro, luego en el ícono inferior,  y por
![image](https://user-images.githubusercontent.com/41264/54390603-e728c100-4670-11e9-9623-a83875cdd464.png)


### ¡A Explorar!

![image](https://user-images.githubusercontent.com/41264/54392714-58b73e00-4676-11e9-8770-131f46dc7b51.png)



### Agregar título a la gráfica

Seleccionar de la parte izquierda

![image](https://user-images.githubusercontent.com/41264/54392665-40dfba00-4676-11e9-8acd-42564b1d567f.png)


Arrastrar hasta la parte superior y agregar el título deseado

![image](https://user-images.githubusercontent.com/41264/54392819-88fedc80-4676-11e9-9e8f-28bc8774b343.png)
