# casita
sala
## El maistro
CARLOS ARTURO MORENO SUSATAMA

## Intergrantes
  * Integrante 1 yo
  * Integrante 2 yo
  * Integrante 3 yo

## LOS PROPIOS KOMANDOS
git pull (informacion actualizada)
git status
git add .
git commit -a -m "fix: modofique readme"
fix y git (para modificar )


Inicializar el Proyecto
Ejecuta este comando en tu terminal para crear un nuevo proyecto Vue 3 con Vite:
npm create vite@latest nombre_proyecto --template vue
 
Luego, entra en la carpeta del proyecto:
cd nombre_proyecto
 
Instalar Dependencias Esenciales
Instala Vue Router, Pinia y Axios:
npm install vue-router pinia axios
 
Ejecutar el Proyecto
Para iniciar el servidor de desarrollo, ejecuta:
npm run dev
 
________________________________________________________________________________________________
Uso de git y Github
1- Para saber el estado de los documentos modificados o creados se usa: 
git status
 
verificar que los archivos que edito esten corregidos
 
2- use el siguiente comando para agregar el contenido que esta en estatus al repo:
git add .
 
3 cree el comentario de lo que hizo teniendo en cuenta:
fix: para modificaciones o correcciones
feat: para describir si creo nuevo codigo en el repo
 
git commit -a -m "fix: o Feat: descripcion de lo que hizo"
 
 
4 para terminar recuerde actualizar el repositorio usando el comando:
 
git push
 
al finalizar estos pasos ningun archivo debe aparecer de colores en su espacio de trabajo o codigo
 
siga estos pasos para tener exito en el desarrollo de las clases y trabajo individual.

________________________________________________________________________________________________

## Manejo de Formularios con PHP

Session_destroy(); // destruye la variable de logeo actual
Session_start(); // Permite iniciar y crea espacio en la memoria de usuario
Session_unset(); // Destruye todas las variables creadas por Session_start();
$_POST["variable"]; // Permite adquirir variables entre el DOM "Se usa para formuloarios"
$_GET["variable"]; // Permite adquirir variables enviadas mediante la url a php
header("location:url_server"); // Envia o redirecciona a un php creado dentro del servidor
exit(); // tenia las variables
