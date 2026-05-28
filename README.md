# testing_automatizado_playwright
Primeras pruebas de automatizaciones utilizando playwright y el controlador de versiones git. 

En este proyecto encontraran plasmado los aprendizajes adquiridos sobre testing automatizado utilizando playwright para testear 
la pagina: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login

La carpeta "OrangeHMR-test" será la protagonista de este proyecto. Allí encontraran la organizacion y automatizacion personal realizada. La misma se fracciona en 5 folders internos:

-"Datos": contiene documentos.json con datos de usuarios ficticios

-"Helper": contiene funciones genericas y repetitivas para optimizar su uso a lo largo del proyecto.

-"mapeos-page": optimizacion para el llamado de distintos elementos de cada modulo de la pagina testeada. 

-"tests_escenario_login": se visualizan multiples casos de prueba automatizados, en principio utilizando el grabador "codegen".

-"test_sidebar": visualizacion de casos de prueba optimizados utilizando funciones reutilizables descriptas en los helpers y mapeos.

En principio la comparativa entre los ultimos dos folder mencionados que contienen casos de prueba se podrá visualizar el avance en practica y aprendizaje de la automatización con playwright. Los test de login se realizaron utilizando el grabador de codegen para luego pasarlos a codigo limpio. Mientras que los test relacionados al sidebar comienzan a utilizar herramientas vistas en clase para reciclar codigo desde el inicio y optimizar la automatizacion de cada uno. 


Por otro lado, en "Repositorio-Programon/branch-3" se encuentran todos los archivos originales forkeados del proyecto original, analizados y estudiados en clase. 

El archivo ".vscode" incluye las extensiones utilizadas en el proyecto. 

Por su parte ".github/workflows" es un documento de ejemplo y modelo de un pipeline. 
