![Logo](/../main/imagenes/logo.png)
# Evaluación Práctica
Resolución a las tareas y preguntas de la evaluación práctica 

## Ejercicio 1
**1. Instalar el IDE Visual Studio Code:**

![Imagen1](/../main/imagenes/vsc.png)

**2. Instalar GIT y GIT Bash:**

   -Git

![Imagen2](/../main/imagenes/git.png)

   -Git Bash

![Imagen3](/../main/imagenes/bash.png)

## Ejercicio 2
**1. ¿Qué es un servidor HTTP?**

     R= Servidor que se encarga de atender las solicitudes web realizadas por el lado cliente, así como de realizar las operaciones correspondientes para entregar una respuesta 

**2. ¿Qué son los verbos HTTP? Mencionar los más conocidos**

     R= Los verbos o métodos HTTP son operaciones que se llevan a cabo sobre un recurso web, como lo es el intercambio de información con una página web
     -GET
     -HEAD
     -POST
     -PUT
     -DELETE
     -TRACE
     -CONNECT
     -OPTIONS
     

**3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**

     R= El request es la solicitud que hace el lado cliente al servidor, mientras que el response es la respuesta que entrega el servidor al cliente
     
     Los headers son elementos que permiten obtener más información en un intercambio entre requests y responses

**4. ¿Qué es un query String? (En el contexto de una url)**

     R= Una sección de una url en donde se pueden colocar campos y sus respectivos valores para una página o proceso determinado

**5. ¿Qué es el response Code? ¿Qué significado tiene los posibles valores devueltos?**

     R= Código de un response que indica si la solicitud fue atendida o no, y posibles razones por las que no fue atendida
     -1xx: información sobre la solicitud que reicibió el servidor
     -2xx: la solicitud fue manejada de manera exitosa
     -3xx: redirección, que indica que se debe tomar medidas para que la solicitud sea existosa
     -4xx: error del lado del cliente
     -5xx: error del lado del servidor
     

**6. ¿Cómo se envía la data en un Get y cómo en un POST?**

     R= En el GET solo se envia la página o datos que se pidio en la solicitud, mientras que con POST se envia una página con datos procesados por el servidor, como los datos de un formulario, por ejemplo 

**7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?**

     R= GET

**8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**

     R= JSON es un formato para almacenar información estructurada que permite el intercambio de datos entre cliente y el servidor
     {
         "nombre": "Alan",
         "apellido": "Mejía"
     }
     
     XML, lenguaje de marcado extensible, que es utilizado también para el intercambio de información en la web mediante contenido estructurado
     <?xml version="1.0"?>
     <auto>
      <marca>Nissan</marca>
      <modelo>Tsuru</modelo>
      <color>Rojo</color>
     </auto>

**9. Explicar brevemente el estándar SOAP**

     R= Es un protocolo basado en XML que es utilizado para el intercambio de información entre programas en ambientes distribuidos

**10. Explicar brevemente el estándar REST Ful**

     R= Son los servicios web que se adhieren a las restricciones y reglas que establece la arquitectura REST(arquitectura cliente-servidor, protocolos sin estado, sistema capado, código on demand, interfaz uniforme)

**11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**

     R= Campos que permiten proporcionar información adicional del lado del cliente en un request. El Content-type es para determinar el tipo de medio de la página
     
## Ejercicio 3
**1. Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json**

![Screen1](/imagenes/ex3_1.png)

**2. Realizar un request POST a la URL anterior, y con body:**
```
{
   "name":"Tu nombre",
   "email":tunombre.tuapellido@procontacto.com.mx
}
```

    Tip: (Marcar la opción “raw” como body)

![Screen2](/imagenes/ex3_2.png)

**3. Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json**

![Screen3](/imagenes/ex3_3.png)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?

    R= En el primer GET aun no estaba agregado el nuevo objeto, mientras que en el segundo se obervan los elementos agregados por el POST del punto 2
