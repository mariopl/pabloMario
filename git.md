
QUERIDOS LECTORES DE WIKIPEDIA: Para proteger nuestra independencia, nunca implementaremos publicidad. No aceptamos dinero proveniente de gobiernos. Sobrevivimos con donaciones de 10 € de promedio. Ahora es el momento en el que te pedimos. Si todos los que leen este mensaje en este momento donaran 2 €, nuestra campaña de recaudación de fondos terminaría en una hora. Somos una pequeña organización sin ánimo de lucro con los gastos de personal, servidores y programas necesarios para mantener uno de los cinco sitios web más importantes del mundo. Wikipedia es algo especial. Es como una biblioteca o un parque público donde todos podemos ir a pensar y aprender. Si Wikipedia te es de utilidad, por favor tómate un minuto para mantenerla abierta y libre de publicidad un año más. Gracias.
Una sola vez	Mensual*
 2 €	 5 €	 10 €	 20 €
 30 €	 50 €	 100 €	   €
Tarjeta de crédito  PayPal  Débito automático
 
¿Problemas al donar? | Otras maneras de donar | Preguntas más frecuentes | Al hacer tu donación, aceptando nuestra política de privacidad de donaciones y compartir tu información con la Fundación Wikimedia y sus proveedores de servicio en los Estados Unidos y otras ubicaciones. *Los pagos recurrentes serán cargados a cuenta por la Fundación Wikimedia hasta que nos notifiques que nos detengamos. Para cada pago, te enviaremos un recibo por correo electrónico, que incluirá un enlace a unas sencillas instrucciones de cancelación.

Git
Para otros usos de este término, véase GIT.
Git
Git-logo.svg
Desarrollador
Junio Hamano, Linus Torvalds
http://git-scm.com/
Información general
Diseñador	Linus Torvalds
Última versión estable	1.9.0 (info)
14 de febrero de 2014; hace 34 días
Género	Control de versiones
Programado en	C, Bourne Shell, Perl1
Licencia	GNU GPL v2
Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Al principio, Git se pensó como un motor de bajo nivel sobre el cual otros pudieran escribir la interfaz de usuario o front end como Cogito o StGIT. 2 Sin embargo, Git se ha convertido desde entonces en un sistema de control de versiones con funcionalidad plena. 3 Hay algunos proyectos de mucha relevancia que ya usan Git, en particular, el grupo de programación del núcleo Linux.
El mantenimiento del software Git está actualmente (2009) supervisado por Junio Hamano, quien recibe contribuciones al código de alrededor de 280 programadores.
Índice  [ocultar] 
1 Características
2 Véase también
3 Referencias
4 Enlaces externos
Características[editar]

El diseño de Git se basó en BitKeeper y en Monotone. 4 5
El diseño de Git resulta de la experiencia del diseñador de Linux, Linus Torvalds, manteniendo una enorme cantidad de código distribuida y gestionada por mucha gente, que incide en numerosos detalles de rendimiento, y de la necesidad de rapidez en una primera implementación.
Entre las características más relevantes se encuentran:
Fuerte apoyo al desarrollo no lineal, por ende rapidez en la gestión de ramas y mezclado de diferentes versiones. Git incluye herramientas específicas para navegar y visualizar un historial de desarrollo no lineal. Una presunción fundamental en Git es que un cambio será fusionado mucho más frecuentemente de lo que se escribe originalmente, conforme se pasa entre varios programadores que lo revisan.
Gestión distribuida. Al igual que Darcs, BitKeeper, Mercurial, SVK, Bazaar y Monotone, Git le da a cada programador una copia local del historial del desarrollo entero, y los cambios se propagan entre los repositorios locales. Los cambios se importan como ramas adicionales y pueden ser fusionados en la misma manera que se hace con la rama local.
Los almacenes de información pueden publicarse por HTTP, FTP, rsync o mediante un protocolo nativo, ya sea a través de una conexión TCP/IP simple o a través de cifrado SSH. Git también puede emular servidores CVS, lo que habilita el uso de clientes CVS pre-existentes y módulos IDE para CVS pre-existentes en el acceso de repositorios Git.
Los repositorios Subversion y svk se pueden usar directamente con git-svn.
Gestión eficiente de proyectos grandes, dada la rapidez de gestión de diferencias entre archivos, entre otras mejoras de optimización de velocidad de ejecución.
Todas las versiones previas a un cambio determinado, implican la notificación de un cambio posterior en cualquiera de ellas a ese cambio (denominado autenticación criptográfica de historial). Esto existía en Monotone.
Resulta algo más caro trabajar con ficheros concretos frente a proyectos, eso diferencia el trabajo frente a CVS, que trabaja con base en cambios de fichero, pero mejora el trabajo con afectaciones de código que concurren en operaciones similares en varios archivos.
Los renombrados se trabajan basándose en similitudes entre ficheros, aparte de nombres de ficheros, pero no se hacen marcas explícitas de cambios de nombre con base en supuestos nombres únicos de nodos de sistema de ficheros, lo que evita posibles, y posiblemente desastrosas, coincidencias de ficheros diferentes en un único nombre.
Realmacenamiento periódico en paquetes (ficheros). Esto es relativamente eficiente para escritura de cambios y relativamente ineficiente para lectura si el reempaquetado (con base en diferencias) no ocurre cada cierto tiempo.
Véase también[editar]

Control de versiones
Programas para control de versiones
Referencias[editar]

Ir a ↑ «git/git.git/tree». git.kernel.org. Consultado el 2009-06-15.
Ir a ↑ Linus Torvalds (08-04-2005). «Re: Kernel SCM saga».
Ir a ↑ Linus Torvalds (23-03-2006). «Re: Errors GITtifying GCC and Binutils».
Ir a ↑ Linus Torvalds (05-05-2006). «Re: [ANNOUNCE] Git wiki». Referencias de los antecesores de Git
Ir a ↑ LKML: Linus Torvalds: Re: Kernel SCM saga
Enlaces externos[editar]

Sitio web oficial
Categorías: Sistemas de Control de Versiones DistribuidosSoftware de 2005
Menú de navegación
Crear una cuentaIniciar sesiónArtículoDiscusiónLeerEditarVer historial

Portada
Portal de la comunidad
Actualidad
Cambios recientes
Páginas nuevas
Página aleatoria
Ayuda
Donaciones
Notificar un error
Imprimir/exportar
Crear un libro
Descargar como PDF
Versión para imprimir
Herramientas
En otros idiomas
العربية
Български
Bosanski
Català
Čeština
Dansk
Deutsch
English
Esperanto
Eesti
فارسی
Suomi
Français
עברית
Hrvatski
Magyar
Bahasa Indonesia
Italiano
日本語
Қазақша
한국어
Latviešu
മലയാളം
Nederlands
Norsk bokmål
Polski
Português
Română
Русский
Simple English
Slovenčina
Svenska
தமிழ்
తెలుగు
ไทย
Türkçe
Українська
Tiếng Việt
中文
Editar los enlaces
Esta página fue modificada por última vez el 17 feb 2014, a las 09:26.
El texto está disponible bajo la Licencia Creative Commons Atribución Compartir Igual 3.0; podrían ser aplicables cláusulas adicionales. Léanse los términos de uso para más información.
Wikipedia® es una marca registrada de la Fundación Wikimedia, Inc., una organización sin ánimo de lucro.
Contacto
Política de privacidadAcerca de WikipediaLimitación de responsabilidadDesarrolladoresVersión para móvilesWikimedia Foundation Powered by MediaWiki
