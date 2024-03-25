# Parte I - Despliegue app React (frontend) en Azure
1. Busca Azure for Students en tu buscador de preferencias e ingresa con el correo institucional.
2. Crea un budget de 1 dólar para la cuenta
   
   a. Una vez hayamos una cuenta. 
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/3af0c5cc-b17a-4404-afb0-a3cdce67145d" height="400">


   b. Escribimos en la barra de búsqueda "budget" y entramos a en la primera opción.
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/08ca222a-362e-49f6-b746-b1837f015184)

   c. En esta parte daremos clic en el boton de "Add" para crear un nuevo budget.
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/bf95d4f4-a12a-4015-9bdf-688bc6caef38" width="830">

   d. Llenamos la información requerida y luego damos en "Next" .                    
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/33b99acb-c05e-46f2-ac99-19c3ca588a68" height="400">

   e. Pondremos un porcentaje y agregaremos un email para que nos avise cuando hayamos consumido ese porcentaje de nuestro budget, luego de esto daremos en "Create" .
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/a02fa745-9029-4a9b-8beb-172d3fcdb7bc" height="400">
   
   f. Ya podemos ver el budget que acabamos de ver.
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/1d88061b-249a-46e4-96b9-2dbbcc2017df" width="830">



   
3. El profesor guía el resto de pasos

   a. En esta parte crearemos una "Static Web app", para esto, en la barra de búsqueda escribiremos "App service" e ingresaremos en la primera opción.
   
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/af1cd96d-caee-41b5-a8aa-62d16cd3184d)

   b. Una vez aquí, daremos en el botón de "Create" y luego seleccionaremos "Static Web App".
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/f6d579b7-48c0-4232-ad72-5d2cecf7b2a7" width="830">

   c. Luego escribimos el nombre de un grupo ya existente o uno que deseemos crear, le ponemos un nombre a nuestra aplicación, en la opción de "source" dejaremos GitHub, luego iniciaremos sesión con nuestra cuenta, la organización seremos nosotros, por lo que debemos dejar en esta parte nuestro nombre de usuario, luego seleccionaremos el repositorio y la rama donde está la aplicación que deseemos desplegar, por último daremos clic en el boton de "Review + create" .
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/e4873910-ed9f-4647-a962-43b3d6d430c3" height="400">
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/9475f2d8-9129-493a-81dc-079c9d78417e" height="300">

   d. Lo siguiente que haremos simplemente es dar en "Create" y esperamos a que la aplicación se termine de crear.
   <img src="https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/eaebd135-c457-47c5-8ed5-b3d9de4e564d" height="400">

   e. Luego de que se cree, daremos clic en "Go to resource" .
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/b6049d3d-430d-45ea-8cdb-13aa9786beae)
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/52522fb4-124f-41e0-9b50-7ad6f87a9cb1)

   f. Ahora iremos al repositorio que pusimos anteriormente y daremos clic en la ventana de "Actions" .
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/2f8759f0-1c49-464f-9a64-05f5afd3a584)

   g. Aquí veremos todos "workflows" que están en ejecución, nos interesa el primero que es el más reciente.
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/95c26b07-97bc-4770-bc54-c09a5b264506)

   h. Aquí podrás ver el estado del "workflows" y tambies puedes volver a re ejecutar todos los trabajos dando clic en el botón "Re-run all jobs", al final de esta operación tendrás el enlace de tu aplicación, o puedes volver a Azure y dar clic en el botón "View app in browser" .
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/ab7ddeff-2d11-4db8-95d8-b9ae7aa1a137)
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/4e6c1dd8-aaa7-43ef-bc47-652880461f3f)
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/a8fe4cac-74db-48bf-b454-26ffaedb630f)

   i. Con esto habremos terminado de desplegar nuestra app React en Azure.
   ![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/1151575b-1cdc-4011-af8e-2ccf33eac7bd)
 

# Parte II - Despliegue app web spring MVC (o spring-boot backend)

## Ejercicio 1: Creacion de base de datos en Azure
1. Inicie Azure Cloud Shell desde el portal. Para implementar en un grupo de recursos, ingrese el siguiente comando
2. Para crear un plan de servicio de aplicaciones (App service plan)
3. Finalmente, cree el servidor MySQL con un nombre de servidor único.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/8b852fba-fe41-46c6-9286-3e164aa037a3)

4. Navegue hasta el grupo de recursos que ha creado. Debería ver un servidor Azure Database for MySQL server aprovisionado. Seleccione el servidor de base de datos.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/5a13a623-50fc-421e-8366-9890dd3bfa0e)

5. Seleccione Overview. Guarde el Server name y el Server admin login name en un bloc de notas.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/8b48addd-bfea-4cc5-96cb-661bc04d909c)

6. Seleccione Overview. Habilite la opción Allow access to Azure services y guarde los cambios. Esto proporciona acceso a los servicios de Azure para todas las bases de datos de su servidor MySQL.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/a8e5cd86-a0ea-49ac-b54f-d55bd8d6e2e5)

## Ejercicio 2: actualización de la configuración de la aplicación web

a. Antes de seguir el tutorial, debe crear una Web App, nos metemos en "App Services", luego seleccionamos "create" y "Web App" .
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/1e3b7e31-2ad2-4e52-89f6-4e58458b380e)

b. Aquí ponemos un nombre y dejamos los valores del "Runtime stack" como aparecen en la foto, luego dejamos plan de precios en la opción gratis y luego damos en "Review + create" .
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/61a66c2f-9c4f-4bde-9ff7-47677e398805)
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/927d2f8e-f8ca-4e4f-891f-906960167355)

c. Por último damos en "Create" y esperamos a que el proceso termine.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/e2573742-4dfe-4f5e-ae29-4b22e8e5027d)

d. Luego de que termine le daremos en la opción de "Go to resource" .
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/4b76b301-25fb-4d32-993b-ed3bd0b1001f)


Ahora si podemos seguir el tutorial:

1. Seleccione Configuration. Establezca Stack settings como se muestra en la imagen a continuación y haga clic en Guardar.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/a818910e-2ee1-4e70-ba6a-ba450e41e843)

2. Seleccione Overview y click en Browse.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/c0bc31be-16fd-4baf-b2bc-587677af15fc)

3. La página web se verá como la imagen de abajo.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/c5e481e6-aa0d-4842-a665-3563e2fbb17c)

4. Desde Azure Portal, seleccione la aplicación web que aprovisionó. Ir a Configuración | Configuración de la aplicación | Cadenas de conexión y haga clic en + Nueva cadena de conexión.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/07fb54da-1685-4512-8a82-5f8ac8cfcac8)

5. En la ventana Agregar/Editar cadena de conexión, agregue una nueva cadena de conexión MySQL con MyDatabase como nombre, pegue la siguiente cadena para el valor y reemplace MySQL Server Name, su nombre de usuario y su contraseña con los valores apropiados. Haga clic en Actualizar.

```
jdbc:mysql://{MySQL Server Name}:3306/alm?useSSL=true&requireSSL=false&autoReconnect=true&user={your user name}&password={your password}
```
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/84b9a95d-8a84-4e09-9f7b-09aa0a7ba0b9)

6. Haga clic en Guardar para guardar la cadena de conexión.

## Ejercicio 3: actualización de la configuración de la aplicación web

- Configuración de la base de datos:
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/29195922-3bbb-4826-a079-20e4446510b1)

- Configuración del servicio FTP en la aplicación web, escribir el siguiente comando en "Startup command".
```
  java -jar /home/site/wwwroot/app.jar -- server.port=80
```
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/4222ceab-9bec-4ac7-9fc5-51c88be3eb10)

luego de configurar esto, vamos a clonar el repositorio https://github.com/PDSW-ECI/spring-mvc-with-bootstrap,luego lo copilaremos para obtener un archivo .jar, es importante cambiar el nombre de este archivo por "app.jar", este archivo estará en la carpeta target del p 
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/41a51ee6-6028-4f32-ba0c-22d453a13213)
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/bff03849-1dd0-4961-b1a7-fae5c4fe6e86)
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/e2e78ef2-869d-40e8-b242-75dae8bc7bd1)

Una vez tengamos este jar, lo que haremos es iniciar un FTP Client, en este caso lo haremos con la ayuda de WinSCP, para ver nuestras credenciales debemos ir a la opción "Deployment Center" en la parte de "FTPS credentials"
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/0840ecaa-75cd-4dcb-8554-87c9ec649c6c)

Abrimos WinSCP, iniciamos sesion con nuestras credenciales, luego buscamos el directorio donde está el archivo .jar que generamos anteriormente y lo arrastramos a la parte del servidor.
![image](https://github.com/Mauricio-A-Monroy/Lab6-CVDS/assets/111905757/d12d9754-eb03-4fd3-8d18-94c078468b98)


 

