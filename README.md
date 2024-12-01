Esta estructura HTML detalla la página web para un hospital, consta de una sección inicial, reseñas, presentación del equipo médico, servicios ofrecidos y el formulario de contacto para dejar a la página. 

[Laboratorio1, Módulo3] En esta ocasión se implementa JSON para manipular y transferir datos en el sitio web del hospital, además de trabajar con estructuras de datos avanzadas y crear algoritmos para optimizar las operaciones con estos datos. Los estudiantes también
practicarán la clonación, fusión y recorrido de objetos, y la implementación de algoritmos como búsqueda y ordenamiento en JavaScript.

------CÓMO ABRIR EL ARCHIVO------

-->descargar el Taller2.raw-->descomprimirlo 
-->VSC-->File-->Open Folder-->LAB 1

------Carpeta y subcarpetas-------
TALLER 2
--images
--JavaScript
  -estructuras.js
  -algoritmos.js
  -json.js
--json
--node_modules
--scss
--index.html
--package
--package-lock
--README

------Explicación de implementaciones en WEB-------

Objetos JSON:
-Se crea una listado de los doctores que contiene información nombre, experiencia, universidad, disponibilidad y contacto. Se anidan los objetos para cumplir ese requerimiento y se utiliza destructuring para mostrar información de un solo doctor.

Operaciones con JSON:
Se añaden botones que pueden hacer las siguientes funciones:
-crea una lista clonada
-juntar dos listas, donde una es de doctores y otra la de su disponibilidad.
-recorrido y stringify muestra la lista de doctores en el navegador y consola.

Estructura de datos:
-implementación de arreglos para almacenar los doctores, agregar doctores y eliminarlos.
-utilización de pilas y colas para almacenar y agendar las citas de los pacientes, así como también la atención de estos mismos.

Programación de algoritmos:
-implementación de un algoritmo que mediante un prompt pregunta por un nombre y busca en la lista de doctores, si lo encuentra da el mensaje y si no, también da el mensaje correspondiente.
-integración de un algoritmo de ordenamiento que ordena los años de experiencia de los doctores basado en un arreglo y los modifica de menor a mayor.
-Basado en la notación Big-O y la complejidad ciclomática, el primer algoritmo de buscar el nombre tuvo la complejidad de convertir el elemento que se buscaba en minúsculas (toLowerCase), debido a que esto hacia que la persona tuviera que poner el nombre exacto para que se encontrara en la lista. 
La parte de ordenar doctores por años de experiencia, sin embargo, implicaba la creación de objetos en un arreglo que incluyera el nombre y experiencia, consecuentemente se debía extraer el año de experiencia y hacer el ordenamiento creando una matriz para verificar que un valor fuera mayor que el anterior, y si se cumplía se debe modificar su posición de índice. 



------CRÉDITOS------
images
https://www.pexels.com/es-es/
https://blog.getbootstrap.com/2022/11/11/bootstrap-icons-1-10-0/
https://github.com/404GamerNotFound/bootstrap-5.3-dark-mode-light-mode-switch
