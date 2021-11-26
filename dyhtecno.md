# La red atrapada

En los comienzos fue un servidor y un navegador. Ambos en la máquina de Tim Berners-Lee en el CERN de Ginebra. De a poco se fue expandiendo por el resto del instituto y desde ahí a las Universidades del mundo. Recuerdo que la primera vez que escuché de la web e internet (aún no sabía diferenciarlas) quise conocerla. Por suerte mi mamá tenía acceso en la Facultad de Ciencias Naturales de la Universidad de Buenos Aires. Un sábado por la mañana, mientras ella daba clases, me quedé en su laboratorio aprendiendo a usar un navegador (supongo que Netscape) y alguno de los primeros buscadores.

Desde ese momento hasta ahora han ocurrido cambios en las tecnologías que utilizamos para buscar información, compartir medios gráficos y para conectarnos a la web. Y así como ahora somos capaces de muchas más cosas que en aquellos primeros años, también hemos perdido algunas capacidades (o están más dificultadas) que hacen que aquella Declaración de la Independencia del Ciberespacio quede como un lindo manifiesto hippie enterrado en la realidad.

Entre las principales características que hicieron popular a la web están:

1. Cualquiera puede tener un servidor web, casi cualquier computadora/equipo puede convertirse en uno con pocos pasos
2. No se necesitan programas especiales para crear una página web, es solo un documento de texto que contiene instrucciones para que una aplicación sepa cómo mostrar el contenido
3. Los navegadores incluyen herramientas que nos permiten aprender cómo otras personas han hecho esas páginas web que tanto nos gustan e imitarlas 
4. Se maneja con estándares consensuados por grupos de personas para que todo funcione de la mejor forma posible y que distintas aplicaciones puedan "entenderse" entre sí
5. Enlaces entre páginas/documentos que nos permiten seguir ampliando la información a través de varios sitios

## Servidores propios

Si bien sigue siendo posible que cada computadora sea un servidor web, los sitios más conocidos usan los servicios de algunas de las grandes empresas, principalmente Amazon AWS o Cloudflare. Esto tiene algunas ventajas claras (no tener que estar dedicando personal propio a realizar el mantenimiento de los servidores y que estas empresas suelen tener mejor velocidad de respuesta ya que son varios cientos de servidores en lugar de uno solo) y permite que muchos proyectos que empiezan pequeños puedan ir creciendo sin preocuparse por la infraestructura de su red. Pero también genera una mayor dependencia a esas empresas.

También entra en esta discusión la soberanía de la información/datos que se tiene en esos servidores. Si, por ejemplo, quien contrata esos servicios es una agencia del Estado, generalmente esa información termina en servidores que físicamente se encuentran en otros países y donde, por lo tanto, priman las leyes extranjeras.

## Un simple editor de texto

Una página web es, en muy resumidas cuentas, un archivo de texto que contiene las instrucciones para que un navegador, esa aplicación que usamos para movernos por la web, sepa como tiene que mostrar el contenido que querramos difundir. Por lo tanto, con cualquier editor de texto básico podemos armar una página web. Y por cualquiera, decimos exactamente eso, aún una de las viejas computadoras de inicios de los 90s tiene un editor de texto que nos va a permitir escribir nuestro contenido y que cualquier navegador pueda verlo. Y si tomamos los recaudos necesarios, el contenido de una página puede ser visto aún en navegadores de décadas pasadas. Si lo comparamos con otros documentos de textos que ya no pueden abrirse porque no existen las aplicaciones propietarias con las que fueron creadas, la diferencia es importantísima para que el contenido de la web pueda estar siempre disponible.

Los sitios que visitamos actualmente no suelen ser creados en esos editores de texto, si no que se arman dinámicamente a partir de cierto código e información de una base de datos. Pero nuestro navegador sigue recibiendo ese "documento de texto" para que pueda leerlo. Y podemos ver ese "documento de texto" para aprender cómo está hecho y copiarlo.

## Aprendizaje por copia

A pesar de lo que suelen enseñarnos en la escuela, aprender de lo que han hecho otros y replicarlo es una de las formas más útiles de incorporar el conocimiento. ¿Te gusta cómo se ve una página o los efectos que hace mientras vas navegando el sitio? Tu navegador te ayuda a aver cómo está hecho y podrás copiarlo. Desde la versión más básica de hacer clic con el botón derecho y "ver el código fuente" hasta las nuevas herramientas para desarrolladores que nos permiten un mayor detalle, todos los navegadores incluyen opciones para que podamos aprender de lo que han hecho otres.

Pero en los últimos tiempos han aparecido casos en los que se quiere bloquear este uso para evitar la copia. Opciones que los dueños de sitios pueden configurar para que el botón derecho no funcione de la misma forma, o las propias herramientas para desarrolladores. Por ejemplo, en [el código del navegador Chrome se está habilitando esta opción](https://mastodon.social/@mhoye/107250459834061486) por pedido de algunas Universidades e Institutos que usaban Google Forms u otros formularios online para realizar los exámenes. Y cómo esos formularios mostraban las respuestas correctas con el botón derecho o las herramientas para desarrolladores, pidieron que se pudieran bloquear esas opciones.

## Interoperabilidad

Cuando Tim Berners-Lee publicó su servidor web dejó en claro que no quería "cerrar" la tecnología con patentes o copyright. Cuanta más gente la usara y participara de las decisiones sobre la web mejor sería el producto. Así se creo, entre otras organizaciones, la W3C que se encarga de diseñar los estándares a partir de los que creamos páginas webs y otras tecnologías accesorias.

Es así que cualquiera puede crear su propio programa de servidor web o navegador, siempre y cuando se ajuste a los estándares que han sido definidos. Pero en los últimos años algunas aplicaciones que se han hecho muy conocidas no permiten esta interoperabilidad, para que uno no pueda tener opciones.

Por ejemplo, el correo electrónico que aún usamos (al menos los que tenemos cierta edad) está manejado por estándares. Mientras se cumplan esos estándares podemos usar cualquier aplicación para leer y responder correos. No estamos obligados a usar un programa específico. No sucede lo mismo con la mayoría de las aplicaciones que usamos para mensajería instantánea o redes sociales (pensemos en whatsapp, twitter o facebook). Estas compañías impiden que otras aplicaciones se conecten con sus servicios y, por lo tanto, si queremos usar Whatsapp tenemos que descargar su aplicación. Y sin embargo existen estándares que permiten la misma funcionalidad y con las que podríamos tener nuestra apliación a elección.

El principal objetivo para que tengamos que descargar su aplicación es mantener a las personas "cautivas" en una aplicación y de esa forma centralizar la publicidad o el uso de los datos que se intercambian por la red. Y mudarse de red no es fácil, ya que como no podremos hablar con la mayoría de las personas hasta que no las convenzamos de salir de la otra aplicación, estaremos solos.

Nuevamente, no es un problema técnico. Es un problema económico (o de negocio). También se relaciona con el último punto, en lugar de tener un ecosistema de servicios interconectados, tenemos muchas aplicaciones que se pelean por nuestra atención, que intentan retenernos el mayor tiempo posible en su pequeño espacio.