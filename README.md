# LABORATORIO #6:
### Integrantes: Wilson Delgado, Juanita Oramas


- - -

#### .NET

Se hace la configuración especificada en los prerrequisitos

![img.png](images/img.png)



**Task 1**

Primero se comienzan creando todos los recursos, como la base de datos. Con las configuraciones respectivas del proyecto.
![img_1.png](images/img_1.png)
Se crea una *app service*, para el ambiente de QA y de producción, 
![img_2.png](images/img_2.png)
![img_3.png](images/img_3.png)
![img_4.png](images/img_4.png)
![img_5.png](images/img_5.png)
![img_6.png](images/img_6.png)

**Task 2**
Se elimina el release existente, ahora se crea un nuevo release usando el template **Azure App Service Deployment** para la etapa de QA.
Y se agrega un artefacto, el cual construye un proyecto a partir de PartsUnlimitedE2E y se procede a configurarlo, luego la etapa de QA también. 
![img_7.png](images/img_7.png)
![img_8.png](images/img_8.png)

Se habilita el trigger del despliegue continuo.
![img_9.png](images/img_9.png)

**Task 3**

Se procede a configurar el Web Site para que tenga conexión con la base de datos.
El proceso se hace tanto para el app service de QA como el de Producción.

![img_10.png](images/img_10.png)
![img_11.png](images/img_11.png)

**Task 4**

Se hace un cambio en uno de los archivos para verificar el despliegue y se genera un nuevo release.

![img_24.png](images/img_24.png)
![img_12.png](images/img_12.png)
![img_13.png](images/img_13.png)
![img_14.png](images/img_14.png)

**Task 5**

Se clona la etapa de QA

![img_15.png](images/img_15.png)

Se configura la gate de la etapa de QA. Se renombra a Prod

![img_16.png](images/img_16.png)
![img_17.png](images/img_17.png)

Se crea un nuevo cambio en los archivos y se verifica el despliegue. El critical bug generado, se arregla y se repite el proceso.

![img_19.png](images/img_19.png)
![img_20.png](images/img_20.png)
![img_21.png](images/img_21.png)

Se aprueba el despliegue a producción.

![img_22.png](images/img_22.png)
Progreso del despligue.

![img_23.png](images/img_23.png)
![img_26.png](images/img_26.png)

**Task 6**

Se configuran Slots de despliegue

![img_30.png](images/img_30.png)
![img_31.png](images/img_31.png)
![img_25.png](images/img_25.png)
![img_32.png](images/img_32.png)

Se hace Swap con el servidor de producción para que los cambios se envíen a este.
![img_33.png](images/img_33.png)


![img_34.png](images/img_34.png)
![img_35.png](images/img_35.png)



