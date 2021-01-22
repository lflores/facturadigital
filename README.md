Documentación del proyecto [Factura Digital Argentina](https://dev.facturadigital.ar)

# Factura Digital Argentina
Factura Digital Argentina es una aplicación web que permite administrar facturas y comprobantes digitales, ingresados al sistema como pdf, o cualquier tipo de imágenes.

Debido a que muchas empresas de servicios comenzaron a enviar las facturas en formato digital es mucho más fácil guardarlas sin tener que acumular papel y llenar carpetas con los comprobantes.

La idea desde el principio fue pensar en el ahorro de papel y almacenarlo en formato digital y nació como una idea ecológica.

Factura Digital NO es un generador de Facturas digitales sino un administrador de las facturas de servicios que habitualmente recibimos en nuestros y nos permite guardarlas y ordenarlas para que sean fáciles de encontrar. Es un organizador de la economía hogareña.

El proyecto aun está en desarrollo, y [https://dev.facturadigital.ar](https://dev.facturadigital.ar) es el único ambiente disponible hasta el momento por lo que puede ser que aun contenga errores, y su uso es bajo la exclusiva responsabilidad del usuario.

El proyecto por el momento no es open source, pero si es libre para su uso "tal y como está".

![Bandeja de entrada](assets/01-cargar-archivos.gif)

Por la misma razón no se da ningún tipo de soporte o responsabilidad en caso que alguien alguien decida usarlo en algún emprendimiento comercial. No nos hacemos responsables por pérdidas o daños a los archivos.

## ¿Qué es?
La herramienta provee una interfase para administrar facturas en formato digital y nació como un proyecto personal por la necesidad de administración de las facturas para la economía familiar, pero con el tiempo fui agregándole cada vez más funcionalidades que me permitan manejar el volumen de los datos que necesitaba.
Como ejemplo en mi cuenta personal tengo actualmente cargados 1400 archivos entre comprobantes y facturas, lo que les da una idea del volumen manejado por la aplicación.

Como creo que el proyecto maduró lo suficiente con las distintas prestaciones, decidí compartirlo por si alguien más le sirve y para que me ayuden a mejorarlo.

## ¿Porqué se llama así?
Se llama Factura Digital Argentina porque como dije el proyecto originalmente fue desarrollado en Argentina, y tiene su código basado en resolver problemas de las facturas argentinas (formato de números, recuperar fechas, etc), pero eso no quiere decir que en algún momento pueda ser exportadoa otro lugares si se hacen los ajustes correspondientes. No está descartado que en algún momento pueda ser portado, mejorado o incluso traducido, ya que su contenido ya se encuentra internacionalizado.

## ¿Cómo lo instalo?
No es necesario instalar ningún programa, por lo que con solo acceder a la página, te pedirá conectarse a tu cuenta de [Google Drive](https://drive.google.com) y así podrá configurarse y guardar allí tus facturas.
Una vez iniciada la aplicación podrás ver que en [Google Drive](https://drive.google.com) creará una carpeta llamada Facturas donde irá depositando todos las facturas o recibos creados.
Esos archivos son tuyos y siempre estarán en tu [Google Drive](https://drive.google.com) por lo que siempre los tendrás disponibles aunque en el futuro rechaces el uso de la aplicación o deniegues el acceso a drive tus archivos siguen siendo tuyos.

## ¿Qué me permite hacer?
El proyecto permite administrar los archivos etiquetarlos, ordenarlos, asociarlos y agregarle la metadata que nos permita administrarlos, incluso tenemos la posibilidad de "abrocharlos" tal como haríamos con cualquier factura de papel. En la bandeja de entrada se pueden cargar los archivos, arrastrándolos y soltándolos desde un administrador de archivos, y simplementes haciendo clic en el botón de upload. Una ver cargados los archivos, se puede agregar la información, como fecha de vencimiento, si es una factura o un recibo, el importe o intentar que cargue esos datos automáticamente haciendo clic en el botón "Voy a tener suerte"

## ¿Donde guarda mis archivos?
El proyecto está integrado con [Google Drive](https://drive.google.com), y nos permite usar nuestra cuenta de Google Drive personal como repositorio de los archivos y dejarlos disponibles para administrarlos o compartirlos. 
Es por ésto que el proyecto no guarda ninguna información personal, ni guarda archivos en servidores del proyecto, sino que se basa en una plataforma provista por Google y sobre ella agrega las funcionalidades de administración y guardado de información y configuración. Como dijimos anteriormente los archivos son solo tuyos, y siempre quedarán guardados en tu Google Drive. 
La información que necesita para ordenar y organizarlos queda guardada en cada uno de los archivos, por lo que ninguna información será subida a ningún servidor propio de la aplicación ni compartida.

## ¿Cómo lo uso?
El objetivo siempre fue organizar los archivos que se agreguen y organizarlos para hacerlos fácil de administrar y encontrar cuando por alguna razón necesitemos llegar a ellos. Similar a gmail o a cualquier herramienta de correo podremos agregarle información que nos permita clasificarlos ordenarlos y ponerlos en "carpetas".

Para ésto cuenta con los siguientes accesos o menues:

* __Entrada:__ Permite agregar los archivos cuando los recibimos y podermos agregar la información que necesitamos para archivarlos, la fecha de vencimiento, la empresa de la factura (Edenor, Movistar, Personal, Edea), si es factura o recibo de pago y el importe.
* __Archivadas:__ Una vez que las facturas o comprobantes tienen sus datos cargados se pueden archivar y sacarlos de la entrada y tenerlos guardados
* __Abrochadas:__ Cuando las facturas o recibos han sido abrochados o adjuntados a otro archivo (por el momento solo permite uno solo) los archivos pasan a estar abrochados.
* __Sin abrochar:__ Aquí podremos ver los archivos del tipo facturas a los cuales aun no se les abrochó el comprobante.
* __Ignoradas:__ En algunos casos podremos subir archivos que luego nos dimos cuenta que no queríamos subirlos. Aquí veremos los que ignoramos en algún momento de la clasificación.
* __Favoritas:__ Probablemente mientras estemos buscando algún comprobante o buscando algún pago en particular, podremos poner algún archivo (factura/recibo) como favorito, para tenerlo al alcance de la mano.
* __Duplicadas:__ (en desarrollo) Aquí debería mostrar aquellos archivos que podrían coincidir con otro, por nombre, empresa o por fecha, y la idea es detectarlos en caso que dos archivos similares hayan sido subidos a la herramienta.
* __Borradas___ Cualquier archivo que hayamos borrado aparecerá en éste listado y nos permitirá recuperarlo en caso que lo hayamos hecho por error

## Me gusta, quiero probarlo ya!!
Si quiere probar puedes hacerlo ya, bajando dos archivos de ejemplo [Archivo1-Comprobante](assets/Archivo1-Comprobante.pdf) y [Archivo1-Factura](assets/Archivo1-Factura.pdf) y comenzar a probar la aplicación.
Como mencioné antes por el momento solo existe configuración para Argentina (detectar empresas y valores numéricos por ejemplo) pero con el tiempo y a medida que crezca podremos incorporar más configuraciones.
Las configuraciones regionales sirven para el uso con el botón "Voy a tener suerte" que intenta descubrir la información dentro del archivo, pero de todas maneras si eso no funciona, siempre tienes la opción de cargar los datos a mano, pero obviamente eso es lo que no queremos ;).

## ¿Cómo colaboro?
Me gustaría mucho que me cuentes que te pareció, me des tu opinión o me propongas algo que te gustaría ver en la herramienta, y con tu devolución podré mejorar la herramienta.
Como dije el objetivo del proyecto no es cobrar por él pero si te gustó y quieres reconocer mi trabajo podrías invitarme un café.

<a href="https://www.buymeacoffee.com/leonardo.flores" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-green.png" alt="Buy Me A Coffee" height="23" width="100" style="border-radius:2px" />

## Próximos pasos
Me quedan aún muchas ideas para implementar, y las tengo debidamente documentadas, pero ya se los iré contando oportunamente, en la medida que tenga tiempo y recursos, ya que ésto lo hago por hobbie.
Algunas de las ideas que tengo son:
* Imprimir: Permitir imprimir desde el adminsitrador
* Bajar archivos comprimidos: Despues de una búsqueda de alguna empresa o algún tipo de archivo, permitir bajar el resultado como un zip, lo que nos permitiría por ejemplo tenér todos los recibos y facturas en formato digital según un criterio, por ejemplo "todas las facturas y recibos de Edenor de los últimos años"
* Mejorar la organización jerárquica: Actualmente en el menú de __Archivadas__ se pueden cambiar tres vistas, lista, por empresa y por fecha. Ésto nos deja navegar la información por un nivel jerárquico pero habría que trabajarlo un poco más.  

# Versión actual
La versión actual es la 0.9.1 y aun sigo trabajando en las correcciones y mejoras, así como también en las funcionalidades que me gustaría que tenga.

# Guía visual

## Cargar archivos
![Subir archivos](assets/01-cargar-archivos.gif)

## Voy a tener suerte
### Factura
![Voy a tener suerte factura](assets/02-voy-a-tener-suerte-factura.gif)

### Comprobante
![Voy a tener suerte comprobante](assets/02-voy-a-tener-suerte-comprobante.gif)

## Corregir datos
![Corregir nombre y datos](assets/03-corregir-tipo-documento-y-nombre.gif)

## Archivar
### Archivadas
![Archivar](assets/04-archivar.gif)
### Navegar archivos
![Navegar](assets/05-navegar-archivadas.gif)

## Abrochar factura y comprobante
![Abrochar](assets/06-abrochar.gif)

## Buscar archivos
![Buscar](assets/07-buscar-archivos.gif)

## ¿Donde guarda los archivos?
![Archivos](assets/08-google-drive.gif)

## Favoritos
![Favoritos](assets/09-favoritas.gif)

## Ignorar (no mostrar archivos sin borrar)
![ignorar](assets/10-ignorar.gif)

