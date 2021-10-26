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

     R= En el GET se envía la página o datos que se pidio en la solicitud, mientras que con POST se envian datos para ser utilizados por el servidor, para almacenarlos o utilizarlos en un proceso, por ejemplo 

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

## Ejercicio 4
Resolución de los modulos de Trailhead en este [enlace](https://trailblazer.me/id/alanmejia)

## Ejercicio 5
Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto (algunos no se relacionan entre sí) cada uno de los siguientes
objetos de Salesforce:

**1. Lead:**
Objeto que registra a los prospectos, es decir aquellos individuos que son clientes potenciales

Datos almacenados:

**Lead Information**

-Name

    -Last Name

-Company

-Lead Status

**Address Information**

**Additional Information**

**Description Information**

**2. Account:**
Objeto que registra las cuentas, entidades que ya han adquirido un producto o servicio y de las cuales se tiene un seguimiento

Datos almacenados:

**Account Information**

-Account Name

**Address Information**

**Additional Information**

**Description Information**

**3. Contact:**
Objeto que registra a los contactos, que son las personas con la que se puede comunicar para solicitar o recibir información, proporcionando diversos medios de contacto

Datos almacenados:

**Contact Information**

-Name
   
    -Last Name

**Address Information**

**Additional Information**

**Description Information**

**4. Opportunity:**
Objeto que registra las oportunidades asociadas a una cuenta. Son situaciones en la que se puede prestar un producto o servicio 

Datos almacenados:

**Opportunity Information**

-Opportunity Name

-Close Date

-Forecast Category

-Probability

-Stage

**Additional Information**

**Description Information**

**5. Product:**
Objeto que registra los productos, con información relacionada para identificación

Datos almacenados:

**Product Information**

-Product Name

**6. PriceBook:**
Objeto que registra los precios de los productos

Datos almacenados:

-Price Book Name

**7. Quote:**
Objeto que registra los precios de los productos o servicios ofertados para una oportunidad

Datos almacenados:

-Id

**8. Asset**
Objeto que registra los artículos ya adquiridos por un cliente

Datos almacenados:

**Asset Information**

-Asset Name

**9. Case**
Objeto que registra los casos, que son eventos en los que se requiere dar soporte al cliente 

Datos almacenados:

**Case Information**

-Case Number

-Status
   
-Case Origin

**Web Information**

**Additional Information**

**Description Information**

**10. Article**
Objeto que registra artículos

Datos almacenados:

-Id


### Relaciones
![Diagrama](/imagenes/diagramarelex5.png)

## Ejercicio 6
A.	Consultar ID haciendo un GET con POSTMAN al WS:

![Imagen1](/imagenes/ex6_1.png)

B.	Agregar un campo al objeto Contact llamado idprocontacto de tipo texto de 255 caracteres. 

![Imagen2](/imagenes/ex6_2.png)

C.	Desarrollar un trigger para que cuando un usuario Modifica o Crea un contacto de Salesforce completando el campo generado en el punto B con el ID del punto A, se invoque al Web Service con el idprocontacto obtenga los datos de email de la respuesta y actualice el campo email del contacto. Usar Playground 1. 

![Imagen3](/imagenes/ex6_3.png)

### Código del Trigger

**SetEmailTrigger**

      trigger SetEmailTrigger on Contact (after insert, after update) {
          SetEmailTriggerHandler.handlerTrigger(Trigger.New);
      }

**SetEmailTriggerHandler**

      public class SetEmailTriggerHandler {
          public static void handlerTrigger(List<Contact> listc){
              for(Contact c : listc){
                  if(c.idprocontacto__c=='-Mmfbo1Pv8PKjTM8ykfo'){
                     EmailCallouts.makeGetCallout('-Mmfbo1Pv8PKjTM8ykfo');  
                  }
              }
          }
      }
   
**EmailCallouts**

      public class EmailCallouts {
          @future (callout=true)
          public static void makeGetCallout(String idp) {
              Contact cont;
              Http http = new Http();
              HttpRequest request = new HttpRequest();
              request.setEndpoint('https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts/'+idp+'.json');
              request.setMethod('GET');
              HttpResponse response = http.send(request);
              // If the request is successful, parse the JSON response.
              if(response.getStatusCode() == 200) {
                  // Deserializes the JSON string into collections of primitive data types.
                  Map<String, Object> results = (Map<String, Object>) JSON.deserializeUntyped(response.getBody());

                  String email = (String)results.get('email');

                  cont = [SELECT Id,Name FROM Contact WHERE idprocontacto__c = '-Mmfbo1Pv8PKjTM8ykfo' LIMIT 1];
                  cont.Email = email;

                  //System.debug('Received the following email:');
                  //System.debug(email);
              }
              upsert cont;
          }
      }
      
## Ejercicio 7
Responder las siguientes preguntas brevemente sobre:

### Soluciones de Salesforce

**A.	¿Qué es Salesforce?**

R= Es un sistema basado en la nube para la prestación de servicios de CRM, marketing, análisis de datos y desarrollo de aplicaciones

**B.	¿Qué es Sales Cloud?**

R= Es la plataforma de CRM de Salesforce para realizar ventas, marketing y soporte de usuario tanto en contextos B2B como B2C

**C.	¿Qué es Service Cloud?**

R= Es la plataforma de CRM de Salesforce para proporcionar servicio al cliente y soporte

**D.	¿Qué es Health Cloud?**

R= Es la plataforma de CRM de Salesforce enfocada en el sector médicco

**E.	¿Qué es Marketing Cloud?**

R= Plataforma de Salesforce enfocada en el Marketing que proporciona herramientas para que los equipos de ventas mejoren su relación con los clientes y mejorar las ventas, a traves del uso de la omnicanalidad 

### Funcionalidades de Salesforce

**A.	¿Qué es un RecordType?**

R= Método para tener diferentes tipos de visualizaciones de los mismos elementos, dependiendo de las características del cliente o transacción

**B.	¿Qué es un ReportType?**

R= Diferentes formas de reportes para reseñar operaciones y datos

**C.	¿Qué es un Page Layout?**

R= Función que permite modificar y editar las páginas y la forma en como se muestran los registros y sus campos

**D.	¿Qué es un Compact Layout?**

R= Es una forma de visualizar los elementos clave de un registro en diversos entornos de Salesforce

**E.	¿Qué es un Perfil?**

R= Es un conjunto de configuraciones y permisos proporcionados a un usuario específico de Salesforce que define el alcance de sus acciones en la plataforma

**F.	¿Qué es un Rol?**

R= Uno de los diferentes niveles de jerarquía de una organización. Determina el nivel de acceso (permisos) que se tiene a los elementos y operaciones

**G.	¿Qué es un Validation Rule?**

R= Una regla que permite verificar los datos ingresados

**H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?**

R= La relación Lookup es una conexión entre dos objetos que comparten ciertos campos, mientras que la Master-Detail es una relación de jerarquía donde un objeto (master) controla ciertos comportamientos de el otro elemento (detail)

**I.	¿Qué es un Sandbox?**

R= Es un entorno para realizar pruebas, en salesforce, es una copia de una org en un entorno separado, se usa para desarrollo y testeo 

**J.	¿Qué es un ChangeSet?**

R= Es una funcionalidad que permite enviar personalizaciones entre orgs (de playground a playground, de sandbox a production org, etc.)

**K.	¿Para qué sirve el import Wizard de Salesforce?**

R= Es una interfaz que permite importar datos de diversos objetos estandar de Salesforce

**L.	¿Para qué sirve la funcionalidad Web to Lead?**

R= Para obtener clientes potenciales a traves de formularios web donde los usuarios proporcionan datos para ser almacenados

**M.	¿Para qué sirve la funcionalidad Web to Case?**

R= Permite la recolección de solicitudes de soporte directamente desde el sitio web para generar automáticamente varios casos a la vez

**N.	¿Para qué sirve la funcionalidad Omnichannel?**

R= Para ofrecer múltiples medios para la atención de servicio al cliente

**O.	¿Para qué sirve la funcionalidad Chatter?**

R= Herramienta que permite colaborar a traves de la interacción en chats, y que puede implementarse en diversos elementos

### Conceptos generales

**A.	¿Qué significa SaaS?**

R= Del inglés “Software as a Service”, software que es comercializado como un servicio más que como un producto, esto a veces implica que se tiene que pagar por una renta periódica de la licencia del software

**B.	¿Salesforce es Saas?**

R= No, es un sistema basado en la nube, sobre todo para ofrecer servicios de CRM (Customer Relationship Management), así como servicios de marketing y análisis de datos, entre otros, además de que no está centralizado

**C.	¿Qué significa que una solución sea Cloud?**

R= Que está en la “nube”, esto es, que se puede acceder a ella a través de cualquier dispositivo vía internet

**D.	¿Qué significa que una solución sea On-Premise?**

R= Que está diseñada para las necesidades de una organzación o empresa determinada, basada en sus características particulares y locales

**E.	¿Qué es un pipeline de ventas?**

R= Es un diagrama que permite visualizar como se empatan los prospectos con el proceso de venta

**F.	¿Qué es un funnel de ventas?**

R= Técnicas y estrategias para mejorar los procesos de ventas, usando metodos científicos y matemáticos

**G.	¿Qué significa Customer Experience?**

R=Son los diferentes elementos que se tienen para medir la satisfacción de los clientes durante todas las etapas del consumo de un producto

**H.	¿Qué significa omnicanalidad?**

R= Son los múltiples medios, de forma no integrada, por los cuales se puede comunicar o llegar a clientes potenciales, para la prestación de un servicio o la venta de algun producto

**I.	¿Qué significa que un negocio sea B2B?¿Qué significa que un negocio sea B2C?¿Qué es un KPI?**

R= Un negocio B2B es aquel que está enfocado en prestar servicios a otros negocios o empresas. Los negocios B2C son los que están enfocados en prestar servicios a usuarios finales. Un KPI es un indicador que permite medir que tan bien se estan logrado los objetivos de negocio

**J.	¿Qué es una API y en qué se diferencia de una Rest API?**

R= Una API o Interfaz de Programación de Aplicaciones es una interfaz que permite que piezas de código o software sea usado por otros programas. Una REST Api es aquella que   sigue los lineamientos y restricciones de la arquitectura REST 

**K.	¿Qué es un Proceso Batch?**

R= Un proceso que se realiza en lotes, siendo estos últimos grandes cantidades de registros

**L.	¿Qué es Kanban?**

R= Es un sistema de organización para realizar tareas que permitan la reducción de tiempo en la producción

**M.	¿Qué es un ERP?**

R= Es un conjunto de aplicaciones de software para la administración de negocios

**N.	¿Salesforce es un ERP?**

R= No, es un sistema basado en la nube, sobre todo para ofrecer servicios de CRM (Customer Relationship Management), así como servicios de marketing y análisis de datos, entre otros
