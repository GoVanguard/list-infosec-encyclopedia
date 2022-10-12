# Enciclopedia GoVanguard InfoSec

Esta es una compilación continua de recursos que hemos encontrado útiles y herramientas que usamos.
Si es nuevo en InfoSec y está buscando una lista concentrada de recursos para comenzar, consulte [Introducción a InfoSec y ciberseguridad](https://github.com/GoVanguard/Getting-into-InfoSec-and-Cybersecurity) .

## Tabla de contenido
- [Recursos](#recursos)</resumen>
  * [Certificaciones de seguridad de la información](#information-security-certifications)
  * [Libros](#libros)
  * [Recursos para abrir cerraduras](#recursos para abrir cerraduras)
  * [Artículos de Ingeniería Social](#artículos-de-ingeniería-social)
  * [Conferencias](#conferencias)
  * [Videos en línea](#videos-en-línea)
  * [Cursos Online Gratuitos](#cursos-online-gratis)
  * [Recursos de formación](#recursos-de-formación)
  * [Hackeo de referencias y hojas de trucos](#hacking-referencias-y-hojas de trucos)
  * [Ejercicios de entrenamiento y práctica](#ejercicios-de-entrenamiento-y-practica)
  * [Canales de Youtube informativos](#canales-de-youtube-informativos)
  * [Ilustraciones y Presentaciones](#ilustraciones-y-presentaciones)
  * [Bases de datos de explotación de Clearnet](#clearnet-exploit-databases)
  * [Awesome Master Lists](#awesome-master-lists)
  * [Bases de conocimiento](#bases-de-conocimiento)

- [Herramientas OSINT utilizadas](#osint-tools-used)
  * [Herramientas OSINT generales](#herramientas-osint-generales)
  * [Búsqueda criptográfica OSINT](#crypto-osint-search)
  * [Búsqueda de registros gubernamentales](#government-record-search)
  * [Motores de búsqueda nacionales](#motores-de-búsqueda-nacionales)
  * [Metabúsqueda](#meta-búsqueda)
  * [Motores de búsqueda de búsqueda visual y agrupación](#visual-search-and-clustering-search-engines)
  * [Búsqueda en sitios similares](#búsqueda-en-sitios-similares)
  * [Búsqueda de documentos y diapositivas](#document-and-slides-search)
  * [Búsqueda en Pastebin](#búsqueda en Pastebin)
  * [Búsqueda de código](#búsqueda-de-código)
  * [Búsqueda en tiempo real, búsqueda en redes sociales y herramientas generales de redes sociales](#real-time-search-social-media-search-and-general-social-media-tools)
  * [Búsqueda en Twitter](#búsqueda-en-twitter)
  * [Búsqueda en Facebook](#búsqueda-en-facebook)
  * [Búsqueda de Instagram] (#búsqueda de instagram)
  * [Búsqueda de Pinterest](#búsqueda-de-pinterest)
  * [Búsqueda de Reddit](#reddit-search)
  * [Búsqueda de VKontakte] (#búsqueda de VKontakte)
  * [LinkedIn](#linkedin)
  * [Búsqueda de blog](#búsqueda-de-blog)
  * [Búsqueda en foros y tableros de discusión](#búsqueda-en-foros-y-tableros-de-discusión)
  * [Comprobación de nombre de usuario](#comprobación de nombre de usuario)
  * [Investigaciones de personal](#investigaciones-personal)
  * [Búsqueda de correo electrónico / Verificación de correo electrónico](#e-mail-search--e-mail-check)
  * [Investigación de números de teléfono](#investigación de números de teléfono)
  * [Investigación de la empresa](#investigación-empresa)
  * [Investigación de dominios e IP](#domain-and-ip-research)
  * [Descubrimiento e investigación de palabras clave](#keywords-discovery-and-research)
  * [Historial web y captura del sitio web](#historial-web-y-captura-del-sitio-web)
  * [Herramientas de idioma](#herramientas-de-idioma)
  * [Búsqueda de imágenes](#búsqueda de imágenes)
  * [Análisis de imagen](#análisis-de-imagen)
  * [Datos y Estadísticas](#datos-y-estadísticas)
  * [Monitoreo web](#monitoreo-web)
  * [Herramientas OCR](#herramientas-ocr)
  * [Colaboración y gestión de proyectos](#colaboración-y-gestión-de-proyectos)
  * [Herramientas de comunicación](#herramientas-de-comunicación)
  * [Calendarios y programación](#calendarios-y-programación)
  * [Mapas Mentales, Mapas Conceptuales y Herramientas de Generación de Ideas](#mapas-mentales-mapas-conceptuales-y-herramientas-de-generación-de-ideas)
  * [Análisis de redes sociales](#análisis-de-redes-sociales)
  * [Búsqueda y enumeración de DNS](#dns-search-and-enumeration)
  * [Herramientas de reconocimiento de red](#herramientas-de-reconocimiento-de-red)
  
- [Herramientas de recuperación de datos y enumeración de explotación](#exploitation-enumeration-and-data-recovery-tools)
  * [Distribuciones de sistemas operativos de pruebas de penetración] (#penetration-testing-os-distributions)
  * [Marcos multiparadigmáticos](#multi-paradigm-frameworks)
  * [Escáneres de vulnerabilidad de red](#escáneres-de-vulnerabilidad-de-red)
  * [Escáneres de vulnerabilidades web](#web-vulnerability-scanners)
  * [Explotación web](#explotación-web)
  * [Herramientas de red](#herramientas-de-red)
  * [Analizadores y rastreadores de protocolo](#analizadores-y-olfateadores-de-protocolo)
  * [Proxies y herramientas MITM](#proxies-and-mitm-tools)
  * [Herramientas de red inalámbrica](#herramientas-de-red-inalámbrica)
  * [Herramientas de seguridad de la capa de transporte](#transport-layer-security-tools)
  * [Criptografía](#criptografía)
  * [Post-explotación](#post-exfiltración)
  * [Herramientas de exfiltración](#herramientas-de-exfiltración)
  * [Analizadores estáticos](#static-analyzers)
  * [Analizadores dinámicos](#analizadores-dinámicos)
  * [Editores hexadecimales](#editores hexadecimales)
  * [Herramientas de análisis de formato de archivo](#file-format-analysis-tools)
  * [Herramientas de evasión de antivirus](#anti-virus-evasion-tools)
  * [Herramientas de craqueo de hash](#herramientas-de-craqueo-de-hash)
  * [Utilidades de Windows](#windows-utilities)
  * [Utilidades GNU Linux](#gnu-linux-utilities)
  * [utilidades macOS](#utilidades-macos)
  * [Herramientas de ingeniería social](#herramientas-de-ingeniería-social)
  * [Herramientas de anonimato](#anonymity-tools)
  * [Herramientas de ingeniería inversa](#herramientas-de-ingeniería-reversa)
  * [Herramientas de canal lateral](#side-channel-tools)
  * [Herramientas forenses](#herramientas-forenses)
  * [Análisis de memoria](#análisis-de-memoria)
  *[Herramientas de generación de imágenes de memoria](#herramientas de generación de imágenes de memoria)
  * [Respuesta al incidente](#respuesta-incidente)
  * [Herramientas Honeypot](#herramientas-honeypot)
  * [Monitoreo e IDS-IPS](#monitoreo-e-ids-ips)
  * [Herramientas físicas](#herramientas-físicas)
  * [Emulación de Adversario](#adversary-emulation)
  * [Herramientas de respuesta a incidentes todo en uno](#herramientas-de-respuesta-a-incidentes-todo-en-uno)
  * [Comunidades](#comunidades)
  * [Herramientas de creación de imágenes de disco](#disk-image-creation-tools)
  * [Herramientas de recolección de evidencia](#herramientas-de-recolección-de-evidencia)
  * [Herramientas de gestión de incidentes](#herramientas-de-gestión-de-incidentes)
  * [Distribuciones forenses de Linux](#linux-forensics-distributions)
  * [Recopilación de pruebas de Linux](#linux-evidence-collection)
  * [Herramientas de análisis de registro](#herramientas-de-análisis-de-registro)
  * [Colección de evidencia OSX](#osx-evidence-collection)
  * [Manuales de respuesta a incidentes](#manuales)
  * [Herramientas de volcado de procesos](#herramientas-de-volcado-de-procesos)
  * [Herramientas de sandboxing/reversing](#sandboxingreversing-tools)
  * [Herramientas de línea de tiempo](#herramientas de línea de tiempo)
  * [Recopilación de pruebas de Windows](#windows-evidence-collection)
  * [Otro otro)
  
- [Licencia](#licencia)

-------------------------------------------------- -------------------------------------------------- --------------------------------------------------

### Recursos

#### Certificaciones de seguridad de la información

* [Hacker ético certificado](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/)
* [Profesional certificado en seguridad de sistemas de información (CISSP)] (https://www.isc2.org/Certifications/CISSP)
* [Ingeniero de pruebas de penetración certificado (CPTE)] (https://www.mile2.com/penetration-testing-engineer-outline/)
* [Seguridad de CompTIA+](https://www.comptia.org/certifications/security)
* [Fundamentos de seguridad de GIAC (GSEC)] (https://www.giac.org/certification/security-essentials-gsec)
* [Kali Linux Certified Professional (KLCP)] (https://home.pearsonvue.com/kali)
* [Experto certificado en seguridad ofensiva (OSCE)] (https://www.offensive-security.com/ctp-osce/)
* [Profesional certificado en seguridad ofensiva (OSCP)] (https://www.offensive-security.com/pwk-oscp/)
* [Experto en Explotación de Seguridad Ofensiva (OSEE)](https://www.offensive-security.com/awe-osee/)
* [Experto web en seguridad ofensiva (OSWE)] (https://www.offensive-security.com/awae-oswe/)
* [Profesional inalámbrico de seguridad ofensiva (OSWP)] (https://www.offensive-security.com/wifu-oswp/)

#### Libros
* El diario de un cazador de errores: una visita guiada a través de la naturaleza de la seguridad del software
* Un Curso Corto sobre Virus Informáticos
* Guía de defensa contra malware AVIEN para empresas
* Pruebas de Penetración Avanzadas: Hackeando las Redes Más Seguras del Mundo
* Criptografía Aplicada: Protocolos, Algoritmos y Código Fuente en C
* Monitoreo de seguridad de red aplicada: recopilación, detección y análisis
* Black Hat Python: Programación Python para Hackers y Pentesters
* Manual del Equipo Azul: Edición de Respuesta a Incidentes: Una guía de campo condensada para el Respondedor de Incidentes de Seguridad Cibernética
* SSL y TLS a prueba de balas: comprensión e implementación de SSL/TLS y PKI para servidores seguros y aplicaciones web
* Guía de examen todo en uno para hackers éticos certificados por la CEH
* Guía de examen todo en uno CISSP
* CISSP: Guía de estudio profesional certificada en seguridad de sistemas de información
* CISSP] (ISC) 2 Guía de estudio oficial para profesionales certificados en seguridad de sistemas de información
* Cuenta atrás para el día cero: Stuxnet y el lanzamiento de la primera arma digital del mundo
* Ingeniería Criptográfica: Principios de Diseño y Aplicaciones Prácticas
* Guerra cibernética: la próxima amenaza a la seguridad nacional y qué hacer al respecto
* Ciberseguridad: protección de infraestructuras críticas contra ataques cibernéticos y guerra cibernética
* Ciberseguridad y ciberguerra: lo que todos deben saber
* Ciberseguridad y Derechos Humanos en la Era de la Cibervigilancia
* Ciberespías: la historia secreta de la vigilancia, la piratería informática y el espionaje digital
* Fundamentos de Ciberseguridad
* Future Crimes: Inside the Digital Underground y la batalla por nuestro mundo conectado
* Ghost in the Wires: Mis aventuras como el hacker más buscado del mundo
* Hackeado de nuevo
* Hackeo Expuesto 7
* Hackeo: el arte de la explotación
* Cómo funciona Linux: lo que todo superusuario debe saber
* Manual de aseguramiento de la información: estrategias efectivas de seguridad informática y gestión de riesgos
* Libro de cocina de secuencias de comandos de Linux Shell
* Análisis forense de redes: seguimiento de piratas informáticos a través del ciberespacio
* Seguridad de la red a través del análisis de datos: creación de conciencia situacional
* Pruebas de penetración: una introducción práctica a la piratería
* Análisis práctico de malware: una guía práctica para diseccionar software malicioso
* Práctica de Monitoreo de Seguridad de Redes
* Protección de su identidad en Internet: ¿Está desnudo en línea?
* Protección y Seguridad en la Supercarretera de la Información
* Inversión: secretos de la ingeniería inversa
* Rtfm: Manual de Campo del Equipo Rojo
* Métricas de seguridad, una guía para principiantes
* Spam Nation: la historia interna del ciberdelito organizado, desde la epidemia mundial hasta la puerta de su casa
* Software encubierto: ofuscación, marca de agua y protección contra manipulaciones para la protección del software
* TCP/IP ilustrado
* El arte de la investigación y defensa de virus informáticosnse
* El Arte del Engaño: Controlando el Elemento Humano de la Seguridad
* El arte de la memoria forense
* La guía para principiantes sobre seguridad de la información
* El libro de códigos: la ciencia del secreto desde el antiguo Egipto hasta la criptografía cuántica
* El manual de planificación de respuesta a incidentes informáticos: planes ejecutables para proteger la información en riesgo
* La brecha de habilidades cibernéticas
* The Hacker Playbook: Guía práctica para las pruebas de penetración
* El libro IDA Pro: la guía no oficial del desensamblador más popular del mundo
* La guía Ncsa para PC y seguridad LAN
* El Manual de Shellcoder: Descubrimiento y Explotación de Agujeros de Seguridad
* El Tao de la supervisión de la seguridad de la red: más allá de la detección de intrusiones
* El manual del pirata informático de aplicaciones web: encontrar y explotar fallas de seguridad
* Thinking Security: detener a los piratas informáticos del próximo año
* Comprender la criptografía: un libro de texto para estudiantes y profesionales
* Somos Anónimos: Dentro del Mundo Hacker de LulzSec, Anónimo y la Insurgencia Cibernética Global
* Vulnerabilidades de aplicaciones web: detectar, explotar, prevenir
* Interiores de Windows
* Gusano: La Primera Guerra Mundial Digital
* [Un motor de búsqueda respaldado por el escaneo de Internet - Ariana Mirian](https://censys.io/static/censys.pdf)
* [Prueba de penetración avanzada de Wil Allsopp, 2017](https://www.amazon.com/dp/1119367689/)
* [Pruebas de penetración avanzadas para entornos altamente seguros por Lee Allen, 2012] (https://www.packtpub.com/product/advanced-penetration-testing-for-highly-secured-environments-the-ultimate-security-guide /9781849517744)
* [Hackeo avanzado de amenazas persistentes: El arte y la ciencia de hackear cualquier organización por Tyler Wrightson, 2014](https://www.amazon.com/dp/0071828362)
* [Manual de hackers de Android por Joshua J. Drake et al., 2014] (https://www.wiley.com/en-us/Android+Hacker%27s+Handbook-p-9781118608647)
* [Black Hat Python: Programación en Python para hackers y pentesters por Justin Seitz, 2014](https://www.amazon.com/dp/1593275900)
* [Btfm: Manual de campo del equipo azul por Alan White y Ben Clark] (https://www.amazon.com/dp/154101636X)
* [Diario del cazador de insectos de Tobias Klein, 2011](https://nostarch.com/bughunter)
* [Manual de capacitación para operadores de campo de selección de cerraduras de la CIA] (https://www.scribd.com/doc/7207/CIA-Lock-Picking-Field-Operative-Training-Manual)
* [Manual del hacker de autos por Craig Smith, 2016] (https://nostarch.com/carhacking)
* [Guía de estudio de certificación CompTIA Security+ SY0-501] (https://www.comptia.org/training/books/security-sy0-501-study-guide)
* [Guía completa de Shodan](https://leanpub.com/shodan)
* [Introducción a Dfir](https://sroberts.medium.com/introduction-to-dfir-d35d5de4c180)
* [Libros de Eddie the Wire](https://www.thriftbooks.com/a/eddie-the-wire/397834/)
* [Aspectos básicos de la seguridad de redes empresariales](https://res.cloudinary.com/peerlyst/image/upload/v1499385854/post-attachments/Essentials_of_Enterprise_Network_Security_wiqsvc.pdf)
* [Fuzzing: Brute Force Vulnerability Discovery por Michael Sutton et al., 2007] (http://www.fuzzing.org/)
* [Ghost in the Wires de Kevin D. Mitnick y William L. Simon, 2011](https://www.hachettebookgroup.com/titles/kevin-mitnick/ghost-in-the-wires/9780316134477/)
* [Gray Hat Hacking El manual del hacker ético por Daniel Regalado et al., 2015] (https://www.amazon.com/dp/0071832386)
* [Hackeando la Xbox por Andrew Huang, 2003](https://nostarch.com/xbox)
* [Seguridad de la información holística para desarrolladores web](paquete)](https://leanpub.com/b/holisticinfosecforwebdevelopers)
* [Kali Linux revelado](https://kali.training/downloads/Kali-Linux-Revealed-1st-edition.pdf)
* [Claves del Reino de Deviant Ollam, 2012](https://www.elsevier.com/books/keys-to-the-kingdom/ollam/978-1-59749-983-5)
* [Selección de cerraduras: detalle excesivo por Solomon](https://www.dropbox.com/s/y39ix9u9qpqffct/Lockpicking%20Detail%20Overkill.pdf?dl=0)
* [Recetario y DVD de Malware Analyst de Michael Hale Ligh et al., 2010](https://www.wiley.com/en-us/Malware+Analyst%27s+Cookbook+and+DVD%3A+Tools+and+ Técnicas+para+Luchar+Código+Malicioso-p-9780470613030)
* [Metasploit: The Penetration Tester's Guide de David Kennedy et al., 2011](https://nostarch.com/metasploit)
* [Network Forensics: Tracking Hackers through Cyberspace por Sherri Davidoff y Jonathan Ham, 2012](https://www.amazon.com/dp/B008CG8CYU/)
* [Evaluación de la seguridad de la red por Chris McNab](https://www.amazon.com/dp/B0043EWUR0)
* [Escaneo de red Nmap por Gordon Fyodor Lyon, 2009](https://nmap.org/book/)
* [Hackeo sin tecnología de Johnny Long y Jack Wiles, 2008](https://www.elsevier.com/books/no-tech-hacking/mitnick/978-1-59749-215-7)
* [Técnicas de inteligencia de código abierto - 8.ª edición de Michael Bazell, 2021](https://www.amazon.com/dp/B08RRDTFF9/)
* [Pruebas de penetración: una introducción práctica a la piratería por Georgia Weidman, 2014] (https://nostarch.com/pentesting)
* [Pruebas de penetración: procedimientos y metodologías del Consejo de la CE, 2010] (https://www.amazon.com/dp/1435483677)
* [Practical Lock Picking de Deviant Ollam, 2012](https://www.elsevier.com/books/practical-lock-picking/ollam/978-1-59749-989-7)
* [Análisis práctico de malware por Michael Sikorski & Andrew Honig, 2012](https://nostarch.com/malware)
* [Análisis práctico de paquetes de Chris Sanders, 2017] (https://nostarch.com/packetanalysis3)
* [Ingeniería inversa práctica de Bruce Dang et al., 2014](https://www.wiley.com/en-us/Practical+Reverse+Engineering%3A+x86%2C+x64%2C+ARM%2C+Windows +Kernel%2C+Herramientas+de+inversión%2C+y+Ofuscación-p-9781118787311)
* [Prueba de penetración profesional por Thomas Wilhelm, 2013](https://www.elsevier.com/books/professional-penetration-testing/wilhelm/978-1-59749-993-4)
* [Ingeniería inversa para principiantes de Dennis Yurichev](https://beginners.re/main.html)
* [Rtfm: Manual de campo del equipo rojo por Ben Clark, 2014](https://www.amazon.com/dp/1494295504/)
* [CÓMO de programación segura](https://dwheeler.com/secure-programs/Secure-Programs-HOWTO/index.html)
* [Ingeniería social en seguridad informática: herramientas, tácticas y técnicas por Sharon Conheady, 2014](https://www.mhprofessional.com/9780071818469-usa-social-engineering-in-it-security-tools-tactics-and -técnicas-grupo)
* [Ingeniería social: El arte de la piratería humana por Christopher Hadnagy, 2010](https://www.wiley.com/en-us/Social+Engineering%3A+The+Art+of+Human+Hacking-p-9780470639535 )
* [El arte del engaño de Kevin D. Mitnick y William L. Simon, 2002](https://www.wiley.com/en-us/The+Art+of+Deception%3A+Controlling+the+Human+ Elemento+de+Seguridad-p-9780471237129)
* [El arte de la explotación de Jon Erickson, 2008](https://nostarch.com/hacking2.htm)
* [El arte de la intrusión de Kevin D. Mitnick y William L. Simon, 2005](https://www.wiley.com/en-us/The+Art+of+Intrusion%3A+The+Real+Stories+ Detrás+de+las+explosiones+de+hackers%2C+Intrusos+y+engañadores-p-9780764569593)
* [El arte de la ciencia forense de la memoria por Michael Hale Ligh et al., 2014](https://www.wiley.com/en-us/The+Art+of+Memory+Forensics%3A+Detecting+Malware+and+ Amenazas+en+Windows%2C+Linux%2C+y+Mac+Memory-p-9781118825099)
* [Los fundamentos de la piratería y las pruebas de penetración por Patrick Engebretson, 2013] (https://www.elsevier.com/books/the-basics-of-hacking-and-penetration-testing/engebretson/978-1-59749- 655-1)
* [El manual de piratas informáticos del navegador de Wade Alcorn et al., 2014] (https://www.wiley.com/en-us/The+Browser+Hacker%27s+Handbook-p-9781118662090)
* [Manual del hacker de bases de datos, David Litchfield et al., 2005](https://www.wiley.com/en-us/The+Database+Hacker%27s+Handbook%3A+Defending+Database+Servers-p- 9780764578014)
* [El libro de jugadas del hacker de Peter Kim, 2014](https://www.amazon.com/dp/1494932636/)
* [El libro IDA Pro de Chris Eagle, 2011](https://nostarch.com/idapro2.htm)
* [Manual del hacker de Mac de Charlie Miller y Dino Dai Zovi, 2009](https://www.wiley.com/en-us/The+Mac+Hacker%27s+Handbook-p-9780470395363)
* [Manual de hackers de aplicaciones móviles de Dominic Chell et al., 2015](https://www.wiley.com/en-us/The+Mobile+Application+Hacker%27s+Handbook-p-9781118958506)
* [La práctica de la supervisión de la seguridad de la red: comprensión de la detección y respuesta a incidentes 9](https://www.amazon.com/gp/product/1593275099)
* [El manual de Shellcoders por Chris Anley et al., 2007](https://www.wiley.com/en-us/The+Shellcoder%27s+Handbook%3A+Discovering+and+Exploiting+Security+Holes%2C +2ª+Edición-p-9780470080238)
* [Manual de hackers de aplicaciones web por D. Stuttard, M. Pinto, 2011] (https://www.wiley.com/en-us/The+Web+Application+Hacker%27s+Handbook%3A+Finding+and +Explotación+de+fallas+de+seguridad%2C+2.ª+edición-p-9781118026472)
* [Acceso no autorizado: pruebas de penetración física para equipos de seguridad de TI por Wil Allsopp, 2010] (https://www.amazon.com/dp/B005DIAPKE)
* [Desenmascarando al ingeniero social: el elemento humano de la seguridad por Christopher Hadnagy, 2014](https://www.wiley.com/en-us/Unmasking+the+Social+Engineer%3A+The+Human+Element+of +Seguridad-p-9781118608579)
* [Python violento de TJ O'Connor, 2012](https://www.elsevier.com/books/violent-python/unknown/978-1-59749-957-6)
* [Windows Internals por Mark Russinovich et al., 2012](https://www.amazon.com/dp/0735648735/)
* [Análisis de la red Wireshark de Laura Chappell y Gerald Combs, 2012](https://www.amazon.com/dp/1893939944)
* [Manual de hackers de iOS por Charlie Miller et al., 2012] (https://www.wiley.com/en-us/iOS+Hacker%27s+Handbook-p-9781118204122)

#### Recursos para abrir cerraduras
* [/r/Lockpicking Subreddit](https://www.reddit.com/r/lockpicking/) - Subreddit dedicado al deporte de lockpicking.
* [Keypicking.com](https://keypicking.com/) - Bullicioso foro en línea para la discusión de lockpicking y locksport.
* [LockWiki](http://lockwiki.com/index.php/Main_Page): referencia impulsada por la comunidad tanto para principiantes como para profesionales en la industria de la seguridad.
* [Lockpicking Forensics](http://www.lockpickingforensics.com/) - Sitio web "dedicado a la ciencia y el estudio de la cerrajería forense".
* [Lockpicking101.com](https://www.lockpicking101.com/): una de las comunidades en línea más antiguas "dedicada al pasatiempo divertido y ético de abrir cerraduras".
* [The Amazing King's Lockpicking pages](http://theamazingking.com/lockpicking.php) - Sitio web de aficionados con páginas detalladas sobre lollaves, herramientas y técnicas de recolección.


#### Artículos de ingeniería social
* [Cómo me ingenie socialmente en instalaciones de alta seguridad] (https://www.vice.com/en/article/qv34zb/how-i-socially-ingeniery-my-self-into-high-security-facilities) - Sophie Daniel
* [Ingeniería social: comprometer a los usuarios con un documento de Office] (https://resources.infosecinstitute.com/certification/social-engineering-compromising-users-using-office-document/) - Infosec Institute
* [Los 7 mejores ataques de ingeniería social de la historia](https://www.darkreading.com/the-7-best-social-engineering-attacks-ever/d/d-id/1319411) - DarkReading
* [Los límites de la ingeniería social](https://www.technologyreview.com/2014/04/16/173156/the-limits-of-social-engineering/) - MIT, Technology Review
* [La lista de lectura de persuasión] (https://www.scottadamssays.com/2018/01/24/persuasion-reading-list-updated-1-18/) - Blog de Scott Adams

#### Conferencias
* (ISC)2 Serie de eventos seguros
* 44CON Londres
* 44 Con
* Simposio de Operaciones Cibernéticas Defensivas de AFCEA
* AppSec Estados Unidos] (Conferencia Nacional OWASP)
* AppSec USA
* Conferencia de Seguridad del Atlántico] (AtlSecCon)
* Lados B
* Serie de eventos Bsides
* Balcón
* Sombrero negro
* Sombrero Negro Estados Unidos
* BruCON
* CCC
* Serie de cumbres ejecutivas de CISO] (solo por invitación)
* Conferencia CSO50
* CanSecOeste
*CarolinaCon
* Cumbre de inteligencia sobre ciberamenazas
* DEF CON
* DeepSec
* Campo de defensa
* DerbyCon
* DerbyCon 8.0
* Ecofiesta
* PRIMERA Conferencia
* Fsec
* HACKMIAMI
* HITB
* ESPERAR
* Hack.lu
* Hack3rCon
* Hacker detenido: opcionalmente incluye capacitación específica para la certificación
* Foros de seguridad de la información de IANS
* Cumbre de Privacidad Global de IAPP
* Simposio IEEE sobre seguridad y privacidad
* Nexo de Seguridad Cibernética de ISACA
* Congreso Mundial Anual ISF
* Serie de foros ejecutivos ISSA CISO
* Conferencia Internacional de la AISS
* Encender
* Infiltrarse
* InfoSec Suroeste
* Mundo de seguridad de la información
* Infoseguridad Europa
* Infoseguridad Europa
* Infoseguridad América del Norte
* Capa Uno
* Nullcon
* Conferencia Nullcon
* Cumbre de Seguridad Abierta
* PhreakNIC
* Conferencia RSA Estados Unidos
* Conferencia Anual SANS
* Conferencias anuales SANS Pen Test
* Conferencias anuales de seguridad SANS
* SEGUNDO ADENTRO
* FUENTE Conferencias Anuales
* Sector Canadá
* Conferencia Secure360
* mundo seguro
* Securi-Tay
* Cumbre de operaciones de seguridad y capacitación
* ShmooCon
* SkyDogCon
* SummerCon
* Tormenta cibernética suiza
* ThotCon
* Simposio de seguridad USENIX
* Conferencia Boletín Virus
* conINT
* CISO seguro

#### Vídeos en línea
* [Dennis Maldonado: ¿Estamos realmente seguros? Omitir los sistemas de control de acceso](https://www.youtube.com/watch?v=jTtdTrMSsPw)
* [Internet de las cosas: Metodología de investigación de IoT](https://www.youtube.com/watch?v=iQCaGxnY4LM)
* [Internet de las cosas: la relación entre IoT y seguridad](https://www.youtube.com/watch?v=LcoEe0LvaBo)
* [Seguridad ofensiva Parte 1 - Conceptos básicos de las pruebas de penetración](https://www.youtube.com/watch?v=GX1go9PDnWY)
* [Campañas de Phishing en Metasploit Pro](https://www.youtube.com/watch?v=XReMP6_f2xU)
* [Serie de miércoles de pizarra Rapid7](https://www.youtube.com/playlist?list=PLMrgKzfE1aINBOpJXCkqPdWcT7YCPZYL3)
* [Spear Phishing con Cobalt Strike](https://www.youtube.com/watch?v=V7UJjVcq2Ao)
  
#### Cursos en línea gratuitos
* [Curso en video de certificación de CompTIA Network+ por videos animados de PowerCert](https://www.youtube.com/watch?v=vrh0epPAC5w)
* [Curso de capacitación CompTIA Security+ SY0-501 del profesor Messer](https://www.youtube.com/playlist?list=PLG49S3nxzAnnVhoAaL4B6aMFDQ8_gdxAy)
* [Curso completo de hacking ético de HackerSploit - Parte 1 de 126](https://www.youtube.com/watch?v=tHd8k54kVs8&list=PLBf0hzazHTGOEuhPQSnq-Ej8jRyXxfYvl)
* [Curso completo de Ethical Hacking de Joseph Delgadillo - Curso de 8 horas](https://www.youtube.com/watch?v=fDeLtKUxTmM)
  
#### Recursos de formación
* [Awesome Hacking Resources] (https://github.com/vitalysim/Awesome-Hacking-Resources) - Se explica por sí mismo.
* [Awesome Web Security](https://github.com/qazbnm456/awesome-web-security) - Enciclopedia de información de seguridad web.
* [Corelan.be](https://www.corelan.be/index.php/articles/): sitio web que contiene muchos recursos de capacitación y tutoriales útiles.
* [Cybrary.it](https://www.cybrary.it/) - Cursos gratuitos en línea.
* [Grupo Enigma](https://www.enigmagroup.org/) - Recurso de capacitación de aplicaciones web.
* [Ejecución de Metasploit y Empire Payloads desde MS Office Document Properties parte 1](https://stealingthe.network/executing-metasploit-empire-payloads-from-ms-office-document-properties-part-1-of-2/ ) - Cómo entregar sigilosamente una carga útil de Metasploit a través de las propiedades del documento de MS Office y una macro simple.
* [Ejecución de Metasploit y Empire Payloads desde MS Office Document Properties parte 2](https://stealingthe.network/executing-metasploit-empire-payloads-from-ms-office-document-properties-part-2-of-2/ ) - Como la parte 1, pero centrándose en Empire en lugar de Metasploit.
* [Hacker101](https://www.hacker101.com/) - Recurso de capacitación en línea.
* [Cómo: macro de oficina multiplataforma de Empire] (https://www.blackhillsinfosec.com/empires-cross-platform-office-macro/) - Cómo utilizar la multiplataforma de Empiremacro maliciosa de MS Office.
* [Introducción a las vulnerabilidades de software, parte 1] (https://opensecuritytraining.info/Exploits1.html): tutorial en línea o en persona que cubre múltiples áreas de explotación de software.
* [Introducción a las vulnerabilidades de software, parte 2: explotación en el entorno de Windows] (https://opensecuritytraining.info/Exploits2.html): tutorial en línea o en persona que cubre múltiples áreas de explotación de software, con énfasis en la explotación de Windows.
* [OpenSecurityTraining.info](https://opensecuritytraining.info/) - Recurso de capacitación en línea gratuito.
* [PentesterLab](https://pentesterlab.com/) - Recursos de capacitación en línea por niveles.
* [Phishing Con Empire](https://enigma0x3.net/2016/03/15/phishing-with-empire/) - Guía sobre phishing con Empire.
* [Phishing con PowerPoint](https://www.blackhillsinfosec.com/phishing-with-powerpoint/) - Guía para lograr que los usuarios desprevenidos abran archivos PPT maliciosos.
  
#### Hackear referencias y hojas de trucos
* [Hoja de referencia de LFI](https://highon.coffee/blog/lfi-cheat-sheet/)
* [Hoja de referencia de escalamiento de privilegios y enumeración de Linux local] (https://github.com/rebootuser/LinEnum)
* [Hoja de trucos de la carga útil de Metasploit](https://netsec.ws/?p=331)
* [Hojas de trucos múltiples de Andrewjkerr] (https://github.com/andrewjkerr/security-cheatsheets)
* [Hoja de referencia de Nmap](https://highon.coffee/blog/nmap-cheat-sheet/)
* [Pentest Recon y Enu Cheatsheet](https://highon.coffee/blog/penetration-testing-tools-cheat-sheet/#recon-and-enumeration)
* [Hoja de trucos de Shell inverso] (https://highon.coffee/blog/reverse-shell-cheat-sheet/)
* [Hoja de referencia de inyección SQL](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/)
* [Hoja de trucos XSS] (https://n0p.net/penguicon/php_app_sec/mirror/xss.html)
* [Hoja de trucos de carga útil XSS] (https://github.com/pgaijin66/XSS-Payloads/blob/master/payload/payload.txt)
  
#### Ejercicios de entrenamiento y práctica
* [Kit de material didáctico CPTE](https://www.mile2.com/product/cpte-e-course-kit/): kit de formación oficial pagado para el examen CPTE.
* [Maldita aplicación web vulnerable (DVWA)](https://dvwa.co.uk/) - Aplicación web PHP/MySQL deliberadamente vulnerable.
* [Gruyere](https://google-gruyere.appspot.com/) - Gruyere es una aplicación web que tiene múltiples errores de seguridad que van desde secuencias de comandos entre sitios y falsificación de solicitudes entre sitios, hasta divulgación de información, denegación de servicio, y ejecución remota de código.
* [Hackear este sitio](https://www.hackthissite.org/) - Ejercicios de seguridad de aplicaciones web.
* [Hack the Box](https://www.hackthebox.eu/) - Laboratorios de pentesting en línea con máquinas virtuales de Windows.
* [Hacker101 CTF](https://ctf.hacker101.com/) - Ejercicios de estilo Webapp CTF.
* [Mutillidae](https://www.irongeek.com/i.php?page=mutillidae/mutillidae-deliberately-vulnerable-php-owasp-top-10) - Mutillidae es una aplicación web gratuita de código abierto proporcionada para permitir para hackear una aplicación web. Se puede instalar en Linux, Windows XP, Windows 7 y Windows 10 usando XAMMP.
* [VM Vulnhub similares a OSCP] (https://www.abatchy.com/2017/02/oscp-like-vulnhub-vms): máquinas virtuales intencionalmente vulnerables que se asemejan a OSCP.
* [OWASP Damn Vulnerable Web Sockets (DVWS)](https://github.com/interference-security/DVWS/) - Aplicación web vulnerable que funciona en sockets web para la comunicación cliente-servidor.
* [OWASP Juice Shop](https://github.com/bkimminich/juice-shop/) - Aplicación web intencionalmente insegura basada en JavaScript.
* [OWASP NodeGoat](https://github.com/OWASP/NodeGoat/) - Incluye aplicaciones web Node.js para aprender los 10 principales de OWASP.
* [OWASP Railsgoat](https://github.com/OWASP/railsgoat) - Una versión vulnerable de Rails que sigue el OWASP Top 10.
* [OWASP SecurityShepard](https://github.com/OWASP/SecurityShepherd/) - Plataforma de capacitación en seguridad de aplicaciones web y móviles.
* [OWASP WebGoat](https://github.com/WebGoat/WebGoat): WebGoat es una aplicación insegura que permite probar las vulnerabilidades que se encuentran comúnmente en las aplicaciones basadas en Java que utilizan componentes de código abierto comunes y populares.
* [Marco de conocimiento de seguridad de OWASP] (https://owasp-skf.gitbook.io/asvs-write-ups/) - Ejercicios de laboratorio del marco de conocimiento de seguridad de OWASP completos con reseñas.
* [Over the Wire: Natas](https://overthewire.org/wargames/natas/) - Desafíos de aplicaciones web.
* [Rapid7 Metsploitable](https://information.rapid7.com/download-metasploitable-2017.html): Metasploitable es esencialmente un laboratorio de pruebas de penetración en una caja, disponible como una máquina virtual VMware (VMX).
* [RopeyTasks](https://github.com/iriusrisk/RopeyTasks) - Aplicación web simple deliberadamente vulnerable.
* [Ejercicios XSS] (https://xss-game.appspot.com/) - Ejercicios de búsqueda de errores de Webapp Cross-site scripting (XSS).

#### Canales informativos de Youtube
* [Computerphile](https://www.youtube.com/user/Computerphile/videos?view=0&sort=p&shelf_id=2) - Conceptos de seguridad de la información.
* [Hacksplained](https://www.youtube.com/c/hacksplained) - Guías y tutoriales de piratería.
* [Hak5](https://www.youtube.com/user/Hak5Darren/featured): herramientas, guías y conceptos de piratería.
* [Loi Liang Yang] (https://www.youtube.com/channel/UC1szFCBUWXY3ESff8dJjjzw/videos) - Guías de piratería.
* [Motasem Hamdan](https://www.youtube.com/channel/UCNSdU_1ehXtGclimTVckHmQ/videos) - Guías de piratería.
* [Byte nulo](https://www.youtube.com/channel/UCgTNupxATBfWmfehv21ym-g) - Guías y conceptos de piratería.
* [Canal de Schuyler Towne](https://www.youtube.com/user/SchuylerTowne/) - Videos de bloqueo y charlas de seguridad.
* [Thenewboston](https://www.youtube.com/user/thenewboston/playlists) - Guías de programación y piratería.
* [bosnianbill](https://www.youtube.com/user/bosnianbill) - videos de selección de cerraduras.

#### Ilustraciones y presentaciones
* [Omisión de UAC "sin archivos" usando sdclt.exe](https://enigma0x3.net/2017/03/17/fileless-uac-bypass-using-sdclt-exe/)
* [Una historia de Citrix](https://rastamouse.me/blog/a-citrix-story/)
* [Guía para atacar confianzas de dominio](https://posts.specterops.io/a-guide-to-attacking-domain-trusts-971e52cb2944)
* [Guía para atacar confianzas de dominio](https://www.harmj0y.net/blog/redteaming/a-guide-to-attacking-domain-trusts/)
* [Guía de Pentester para el alcance grupal] (https://www.harmj0y.net/blog/activedirectory/a-pentesters-guide-to-group-scoping/)
* [Una guía de lectura para equipos de GPO y OU](https://wald0.com/?p=179)
* [Abusar de los permisos de Active Directory con PowerView](https://www.harmj0y.net/blog/redteaming/abusing-active-directory-permissions-with-powerview/)
* [Abusando de DCOM para otra técnica de movimiento lateral](https://bohops.com/2018/04/28/abusing-dcom-for-yet-another-lateral-movement-technique/)
* [Abuso de privilegios de DNSAdmins para escalada en Active Directory](http://www.labofapenetrationtester.com/2017/05/abusing-dnsadmins-privilege-for-escalation-in-active-directory.html)
* [Abuso de funciones exportadas e interfaces DCOM expuestas para la ejecución de comandos Pass-Thru y movimiento lateral](https://bohops.com/2018/03/17/abusing-exported-functions-and-exposed-dcom-interfaces-for- paso-a-traves-de-ejecucion-de-comando-y-movimiento-lateral/)
* [Abuso de permisos de GPO](https://www.harmj0y.net/blog/redteaming/abusing-gpo-permissions/)
* [Abuso de funciones de Microsoft Word para phishing: "subDoc"](https://rhinosecuritylabs.com/research/abusing-microsoft-word-features-phishing-subdoc/)
* [Abuso de la estructura de registro COM: CLSID, LocalServer32 e ImprocServer32](https://bohops.com/2018/06/28/abusing-com-registry-structure-clsid-localserver32-inprocserver32/)
* [Acceso al portapapeles desde la pantalla de bloqueo en Windows 10 Parte 1](https://oddvar.moe/2017/01/24/accessing-clipboard-from-the-lock-screen-in-windows-10/)
* [Acceso al portapapeles desde la pantalla de bloqueo en Windows 10 Parte 2](https://oddvar.moe/2017/01/27/access-clipboard-from-lock-screen-in-windows-10-2/)
* [Explotación posterior sin agente](https://www.youtube.com/watch?v=QbjuO5IlpBU)
* [Agresor PowerView](https://threat.tevora.com/aggressor-powerview/)
* [AppLocker - Estudio de caso - ¿Qué tan inseguro es realmente? Parte 1](https://oddvar.moe/2017/12/13/applocker-case-study-how-insecure-is-it-really-part-1/)
* [AppLocker - Estudio de caso - ¿Qué tan inseguro es realmente? Parte 2](https://oddvar.moe/2017/12/21/applocker-case-study-how-insecure-is-it-really-part-2/)
* [¿Estamos realmente seguros? Hackear sistemas de control de acceso](https://www.slideshare.net/DennisMaldonado5/hacking-access-control-systems)
* [Búsqueda de administrador de derivados automatizado](https://wald0.com/?p=14)
* [Awesome Bug Bounty] (https://github.com/djadmin/awesome-bug-bounty)
* [Impresionante CTF] (https://github.com/apsdehal/awesome-ctf)
* [Seguridad impresionante de ICS] (https://github.com/hslatman/awesome-industrial-control-system-security)
* [Awesome Lockpicking](https://github.com/fabacab/awesome-lockpicking)
* [Impresionante Yara](https://github.com/InQuest/awesome-yara)
* [Trayendo los hashes a casa con reGeorg & Empire](https://sensepost.com/blog/2016/bringing-the-hashes-home-with-regeorg-empire/)
* [Evitar AMSI a través del secuestro del servidor COM] (https://posts.specterops.io/bypassing-amsi-via-com-server-hijacking-b8a3354d1aff)
* [Omitir la lista blanca de aplicaciones con BGinfo](https://oddvar.moe/2017/05/18/bypassing-application-whitelisting-with-bginfo/)
* [Omisión de Device Guard UMCI usando CHM - CVE-2017-8625](https://oddvar.moe/2017/08/13/bypassing-device-guard-umci-using-chm-cve-2017-8625/)
* [Omitir UAC usando rutas de aplicaciones](https://enigma0x3.net/2017/03/14/bypassing-uac-using-app-paths/)
* [Inyección celular](http://blog.7elements.co.uk/2013/01/cell-injection.html)
* [ClickOnce, Twice or Thrice: una técnica para la ingeniería social y la ejecución de comandos no confiables](https://bohops.com/2017/12/02/clickonce-twice-or-thrice-a-technique-for-social-engineering -y-ejecución-de-comandos-no-de-confianza/)
* [Clonación y alojamiento de portales cautivos malvados mediante una piña Wi-Fi](https://blog.inspired-sec.com/archive/2017/01/10/cloning-captive-portals.html)
* [Secuestro de CloudFront](https://www.mindpointgroup.com/blog/pen-test/cloudfront-hijacking/)
* [Cobalt Strike: ¿cuál es la técnica de phishing o el exploit?](https://blog.cobaltstrike.com/2014/12/17/whats-the-go-to-phishing-technique-or-exploit/)
* [Certificado de firma de códigoificar ataques y defensas de clonación](https://posts.specterops.io/code-signing-certificate-cloning-attacks-and-defenses-6f98657fc6ec)
* [Colbalt Strike - documentación de Spear Phishing] (https://www.cobaltstrike.com/help-spear-phish)
* [Vulnerabilidades separadas por comas](https://www.contextis.com/es/blog/vulnerabilidades-separadas-por-comas)
* [Exfiltración de datos DNS: ¿Qué es esto y cómo se usa?](https://cuongmx.medium.com/dns-data-exfiltration-what-is-this-and-how-to-use-2f6c69998822)
* [Tunelización de DNS](https://resources.infosecinstitute.com/topic/dns-tunnelling/)
* [Exfiltración de datos a través del canal encubierto de solicitud de DNS: DNSExfiltrator](https://www.kitploit.com/2018/01/dnsexfiltrator-data-exfiltration-over.html)
* [Exfiltración de datos mediante inyección de fórmula](https://notsosecure.com/data-exfiltration-formula-injection/)
* [Defensa en profundidad](https://oddvar.moe/2017/09/13/defense-in-depth-writeup/)
* [DiskShadow: el regreso de la evasión de VSS, la persistencia y la extracción de la base de datos de Active Directory](https://bohops.com/2018/03/26/diskshadow-the-return-of-vss-evasion-persistence-and-active -directorio-base-de-datos-extracción/)
* [Administración de dominio a través de dominios alternativos de Cloudfront](https://www.mdsec.co.uk/2017/02/domain-fronting-via-cloudfront-alternate-domains/)
* [Descargar contraseñas de texto sin cifrar para todos los administradores del dominio mediante Mimikatz DCSync](https://adsecurity.org/?p=2053)
* [Volcado de hash de contraseña de dominio](https://pentestlab.blog/2018/07/04/dumping-domain-password-hashes/)
* [Empire Domain Fronting](https://www.xorrior.com/Empire-Domain-Fronting/)
* [Imperio sin PowerShell](https://isec.ne.jp/wp-content/uploads/2017/08/30Imperio-sin-PowerShell.pdf)
* [Redes restringidas de salida de escape y evasión] (https://www.optiv.com/explore-optiv-insights/blog/escape-and-evasion-egressing-restricted-networks)
* [Macros de Excel con PowerShell](https://4sysops.com/archives/macros-de-excel-con-powerShell/)
* [Ejecutar comandos y omitir AppLocker con secuencias de comandos de diagnóstico de PowerShell](https://bohops.com/2018/01/07/ejecutar-comandos-y-omitir-applocker-con-secuencias de comandos de diagnóstico de PowerShell/)
* [Explotación de variables de entorno en tareas programadas para omisión de UAC](https://www.tiraniddo.dev/2017/05/exploiting-environment-variables-in.html)
* [Extendiendo BloodHound para Red Teamers](https://www.youtube.com/watch?v=Pn7GWRXfgeI)
* [Búsqueda de dominios de Azure frontales de dominio](https://theobsidiantower.com/2017/07/24/d0a7cfceedc42bdf3a36f2926bd52863ef28befc.html)
* [Primera entrada: bienvenida y omisión de UAC sin archivos](https://winscripting.blog/2017/05/12/first-entry-welcome-and-uac-bypass/)
* [De Pass-the-Hash a Pass-the-Ticket sin dolor](https://resources.infosecinstitute.com/topic/pass-hash-pass-ticket-no-pain/)
* [Obtención de productos con CrackMapExec: Parte 1](https://byt3bl33d3r.github.io/obtención-de-los-productos-con-crackmapexec-part-1.html)
* [Obtención de productos con CrackMapExec: Parte 2](https://byt3bl33d3r.github.io/obtención-de-los-productos-con-crackmapexec-part-2.html)
* [Fortalecer Windows con AppLocker - Basado en el caso de estudio Parte 1](https://oddvar.moe/2017/12/13/harden-windows-with-applocker-based-on-case-study-part-1/)
* [Fortalecer Windows con AppLocker - Basado en el estudio de caso Parte 2](https://oddvar.moe/2017/12/21/harden-windows-with-applocker-based-on-case-study-part-2/)
* [Ocultar claves de registro con PSReflect](https://posts.specterops.io/hiding-registry-keys-with-psreflect-b18ec5ac8353)
* [Cómo identifiqué los dominios CloudFront de 93k Domain-Frontable](https://www.peew.pw/blog/2018/2/22/how-i-identified-93k-domain-frontable-cloudfront-domains)
* [Cómo ofuscar JacaScript en Metasploit](https://github.com/rapid7/metasploit-framework/wiki/How-to-ofuscate-JavaScript-in-Metasploit)
* [Evasión en memoria](https://blog.cobaltstrike.com/2018/02/08/in-memory-evasion/)
* [Interceptación de contraseñas con Empire and Winning](https://sensepost.com/blog/2016/intercepting-passwords-with-empire-and-winning/)
* [Introducción al uso de GScript para equipos rojos](http://lockboxx.blogspot.com/2018/02/intro-to-using-gscript-for-red-teams.html)
* [Presentamos a BloodHound](https://wald0.com/?p=68)
* [Introducción a Metasploit: Explotación de aplicaciones web](https://www.slideshare.net/DennisMaldonado5/metasploit-for-web-workshop)
* [Segregación de red de salto con RDP] (https://rastamouse.me/blog/rdp-jump-boxes/)
* [Kerberoasting sin Mimikatz](https://www.harmj0y.net/blog/powershell/kerberoasting-sin-mimikatz/)
* [Trucos de Kerberos Party: armamento de fallas del protocolo Kerberos] (http://www.exumbraops.com/blog/2016/6/1/kerberos-party-tricks-weaponizing-kerberos-protocol-flaws)
* [Movimiento lateral usando aplicación Excel y docm](https://enigma0x3.net/2017/09/11/movimiento-lateral-usando-aplicacion-excel-y-dcom/)
* [Lay of the Land con Bloodhound](https://threat.tevora.com/lay-of-the-land-with-bloodhound/)
* [LethalHTA - Una nueva técnica de movimiento lateral usando DCOM y HTA](https://codewhitesec.blogspot.com/2018/07/lethalhta.html)
* [Aprovechamiento de la técnica de obtención y ejecución de INF-SCT para derivación, evasión y persistencia](https://bohops.com/2018/02/26/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion-persistence/)
* [Aprovechamiento de la técnica de obtención y ejecución de INF-SCT para eludir, evasión y persistencia](https://bohops.com/2018/03/10/leveraging-inf-sct-fetch-execute-techniques-for-bypass-evasion -persistencia-parte-2/)
* [Carga de archivos binarios DLL/CPL ADS de flujo de datos alternativos para omitir AppLocker](https://bohops.com/2018/01/23/loading-alternate-data-stream-ads-dll-cpl-binaries-to-bypass- bloqueador de aplicaciones/)
* [Solución de contraseña de administrador local (LAPS) - Parte 1](https://rastamouse.me/blog/laps-pt1/)
* [Solución de contraseña de administrador local (LAPS) - Parte 2](https://rastamouse.me/blog/laps-pt2/)
* [Enumeración de grupos locales](https://www.harmj0y.net/blog/redteaming/local-group-enumeration/)
* [Ejecución de código sin macros en MSWord](https://sensepost.com/blog/2017/macro-less-code-exec-in-msword/)
* [Microsoft LAPS Security y Active Directory LAPS Configuration Recon](https://adsecurity.org/?p=3164)
* [Microsoft Office - Hashes NTLM a través de Frameset](https://pentestlab.blog/2017/12/18/microsoft-office-ntlm-hashes-via-frameset/)
* [Cargas útiles de macrophishing multiplataforma](https://malcomvetter.medium.com/multi-platform-macro-phishing-payloads-3b688e8eff68)
* [Mi primera vez con BloodHound](https://blog.cobaltstrike.com/2016/12/14/my-first-go-with-bloodhound/)
* [Consideraciones de OPSEC para comandos Beacon](https://blog.cobaltstrike.com/2017/06/23/opsec-considerations-for-beacon-commands/)
* [Ingeniería social OWASP: el arte de la piratería humana] (https://owasp.org/www-pdf-archive/Presentation_Social_Engineering.pdf)
* [Almacenamiento de datos cifrados ofensivos](https://www.harmj0y.net/blog/redteaming/offensive-encrypted-data-storage/)
* [Omisión de enlaces seguros de Office 365](https://oddvar.moe/2018/01/03/office-365-safe-links-bypass/)
* [Formularios y conchas de Outlook](https://sensepost.com/blog/2017/outlook-forms-and-shells/)
* [Página de inicio de Outlook - Otro vector de regla](https://sensepost.com/blog/2017/outlook-home-page-another-ruler-vector/)
* [Pass-the-Hash is Dead: Long Live LocalAccountTokenFilterPolicy](https://www.harmj0y.net/blog/redteaming/pass-the-hash-is-dead-long-live-localaccounttokenfilterpolicy/)
* [Persistencia usando Globalflags en opciones de ejecución de archivo de imagen - Oculto de Autoruns.exe](https://oddvar.moe/2018/04/10/persistence-using-globalflags-in-image-file-execution-options-hidden- de-autoruns-exe/)
* [Persistencia usando RunOnceEx - Oculto de Autoruns.exe](https://oddvar.moe/2018/03/21/persistence-using-runonceex-hidden-from-autoruns-exe/)
* [Phishing contra vista protegida](https://enigma0x3.net/2017/07/13/phishing-contra-vista-protegida/)
* [PowerPoint y Acciones Personalizadas](https://cofense.com/powerpoint-and-custom-actions/)
* [PowerShell Empire Stagers 1: phishing con macro de oficina y evasión de AV](https://fzuckerman.wordpress.com/2016/10/06/powershell-empire-stagers-1-phishing-with-an-office-macro -y-evadir-avs/)
* [PowerShell sin PowerShell: cómo omitir la lista blanca de aplicaciones, las restricciones ambientales y AV] (https://www.blackhillsinfosec.com/powershell-without-powershell-how-to-bypass-application-whitelisting-environment-restrictions-av/ )
* [Guía práctica para la retransmisión de NTLM en 2017](https://byt3bl33d3r.github.io/practical-guide-to-ntlm-relaying-in-2017-aka-getting-a-foothold-in-under-5-minutes .html)
* [Doppleganging de procesos: una nueva forma de suplantar un proceso](https://hshrzd.wordpress.com/2017/12/18/process-doppelganging-a-new-way-to-impersonate-a-process/)
* [Poner datos en flujos de datos alternativos y cómo ejecutarlos](https://oddvar.moe/2018/04/11/putting-data-in-alternate-data-streams-and-how-to-execute-it -parte 2/)
* [Poner datos en flujos de datos alternativos y cómo ejecutarlos](https://oddvar.moe/2018/01/14/putting-data-in-alternate-data-streams-and-how-to-execute-it /)
* [Perspectivas del equipo rojo sobre hosts de Google con dominio HTTPS mediante Cobalt Strike](https://www.cyberark.com/resources/threat-research-blog/perspectivas-del-equipo-rojo-sobre-https-dominio-frente-google- hosts-usando-cobalt-strike)
* [Equipo rojo operando en un entorno moderno](https://owasp.org/www-pdf-archive/Red_Team_Operating_in_a_Modern_Environment.pdf)
* [Tostar AS-REP](https://www.harmj0y.net/blog/activedirectory/roasting-as-reps/)
* [Descubrimiento de SPN](https://petestlab.blog/2018/06/04/spn-discovery/)
* [Escaneo de privilegios de Active Directory y cuentas privilegiadas](https://adsecurity.org/?p=3658)
* [PoC Simple de Fronting de Dominio con GAE C2 Server](https://www.securityartwork.es/2017/01/31/simple-domain-fronting-poc-with-gae-c2-server/)
* [Spear Phishing 101](https://blog.inspired-sec.com/archive/2017/05/07/Phishing.html)
* [Kerberoasting dirigido](https://www.harmj0y.net/blog/activedirectory/targeted-kerberoasting/)
* [Los peligros absurdamente subestimados de la inyección CSV] (http://georgemauer.net/2017/10/07/csv-injection.html)
* [El derecho de usuario más peligroso del que probablemente nunca haya oído hablar](https://www.harmj0y.net/blog/activedirectory/the-most-dangerous-user-right-you-probably-have-never-heard-de/)
* [The PowerView PowerUsage Series #1 - Enumeración masiva de perfiles de usuarios](http://www.harmj0y.net/blog/powershell/the-powerview-powerusage-series-1/)
* [The PowerView PowerUsage Series #2 - Mapeo de nombres cortos de computadora con el catálogo global] (http://www.harmj0y.net/blog/powershell/the-powerview-powerusage-series-2/)
* [The PowerView PowerUsage Series #3 - Enumeración de derechos de edición de GPO en un dominio externo](http://www.harmj0y.net/blog/powershell/the-powerview-powerusage-series-3/)
* [The PowerView PowerUsage Series #4 - Búsqueda de ACE de confianza cruzada](http://www.harmj0y.net/blog/powershell/the-powerview-powerusage-series-4/)
* [Dirección de confianza: un habilitador para la enumeración de Active Directory y la explotación de la confianza](https://bohops.com/2017/12/02/trust-direction-an-enabler-for-active-directory-enumeration-and-trust- explotación/)
* [Ultimate AppLocker ByPass List](https://github.com/api0cradle/UltimateAppLockerByPassList)
* [Monitoreo de API de usuario y detección de inyección de código] (https://0x00sec.org/t/userland-api-monitoring-and-code-injection-detection/5565)
* [Uso de SQL Server para atacar un bosque de confianza] (http://www.labofapenetrationtester.com/2017/03/using-sql-server-for-attacking-forest-trust.html)
* [Uso de un archivo SCF para recopilar hashes](https://1337red.wordpress.com/using-a-scf-file-to-gather-hashes/)
* [Uso de robots.txt para localizar sus objetivos](http://www.behindthefirewalls.com/2013/07/using-robotstxt-to-locate-your-targets.html)
* [Dominios SSL de CloudFront validados](https://medium.com/@vysec.private/validated-cloudfront-ssl-domains-27895822cea3)
* [Vshadow: abuso del servicio Volume Shadow para evasión, persistencia y extracción de base de datos de Active Directory](https://bohops.com/2018/02/10/vshadow-abusing-the-volume-shadow-service-for-evasion -persistencia-y-extracción-de-base-de-datos-de-directorio-activo/)
* [Persistencia WMI con Cobalt Strike](https://blog.inspired-sec.com/archive/2017/01/20/WMI-Persistence.html)
* [Inyección WSH: un estudio de caso] (https://posts.specterops.io/wsh-injection-a-case-study-fd35f79d29dd)
* [Convertir la ciencia de datos en armas para la ingeniería social: suplantación de identidad (spear phishing) E2E automatizada en Twitter](https://www.blackhat.com/docs/us-16/materials/us-16-Seymour-Tully-Weaponizing-Data-Science-For -Social-Engineering-Automated-E2E-Spear-Phishing-On-Twitter.pdf)
* [Semana de Evadir Microsoft ATA](http://www.labofapenetrationtester.com/2017/08/week-of-evading-microsoft-ata-day1.html)
* [Tokens de acceso de Windows y credenciales alternativas](https://blog.cobaltstrike.com/2015/12/16/windows-access-tokens-and-alternate-credentials/)
* [Omisión de reglas de reducción de superficie de ataque de Windows Defender](https://oddvar.moe/2018/03/15/windows-defender-attack-surface-reduction-rules-bypass/)
* [Windows Oneliners para descargar Remote Payload y ejecutar código arbitrario](https://arno0x0x.wordpress.com/2017/11/20/windows-oneliners-to-download-remote-payload-and-execute-arbitrary-code/ )
* [Lista de comprobación de escalamiento de privilegios de Windows](https://github.com/netbiosX/Checklists/blob/master/Windows-Privilege-Escalation.md)
* [seguridad-de-android-impresionante](https://github.com/ashishb/seguridad-de-android-impresionante)
* [Presentaciones y blogs de harmj0y - Explotación de Windows y Active Directory](https://www.harmj0y.net/blog/)
* [Funcionalidad de mavinject.exe deconstruida] (https://posts.specterops.io/mavinject-exe-funcionalidad-deconstruida-c29ab2cf5c0e)
* [sg1: navaja suiza para encriptación de datos, exfiltración y comunicación encubierta](https://securityonline.info/sg1-swiss-army-knife/)

#### Bases de datos de explotación de Clearnet
* [0day.today](https://0day.today/)
* [Impresionante PoC de CVE] (https://github.com/qazbnm456/awesome-cve-poc)
* [Contagio](http://contagiodump.blogspot.com/)
* [Explotar-DB](https://www.exploit-db.com/)
* [InfoSec - CERT-PA](https://infosec.cert-pa.it/analyze/submission.html)
* [MalShare](https://malshare.com/)
* [Seguridad de la tormenta de paquetes] (https://packetstormsecurity.com/)
* [Rastreador h3x](http://tracker.h3x.eu/)
* [Bóveda VX] (http://vxvault.net/ViriList.php)
* [VirusBay](https://beta.virusbay.io/)
* [VirusShare](https://virusshare.com/)
* [VirusSign](http://www.virussign.com/)
* [Código fuente del troyano Zeus](https://github.com/Visgean/Zeus)
* [elZoo](https://github.com/ytisf/theZoo)

#### Impresionantes listas maestras
* [También piratería] (https://github.com/carpedm20/awesome-hacking)
* [Análisis de seguridad de Android] (https://github.com/ashishb/android-security-awesome)
* [Seguridad de la aplicación](https://github.com/paragonie/awesome-appsec)
* [Recompensa por errores](https://github.com/djadmin/awesome-bug-bounty)
* [Prueba de conceptos CVE](https://github.com/qazbnm456/awesome-cve-poc)
* [Capturar la bandera] (https://github.com/apsdehal/awesome-ctf)
* [Desarrollo de exploits](https://github.com/FabioBaroni/awesome-exploit-development)
* [Método forense](https://github.com/Cugu/awesome-forensics)
* [Listas de hacking](https://github.com/udpsec/awesome-hacking-lists)
* [Recursos de piratería] (https://github.com/vitalysim/Awesome-Hacking-Resources)
* [Hackeo](https://github.com/jekil/awesome-hacking)
* [Honeypot](https://github.com/paralax/awesome-honeypots)
* [Respuesta al incidente](https://github.com/meirwah/awesome-incident-response)
* [Seguridad del sistema de control industrial](https://github.com/hslatman/awesome-industrial-control-system-security)
* [ganzúa](https://github.com/fabacab/awesome-lockpicking)
* [Análisis de malware](https://github.com/rshipp/awesome-malware-analysis)
* [OSINT](https://github.com/jivoi/awesome-osint)
* [Herramientas de captura de paquetes](https://github.com/caesar0301/awesome-pcaptools)
* [PenTesting](https://github.com/x0x8x/awesome-pentester)
* [Pruebas de penetración](https://github.com/enaqx/awesome-pentest/) - Con el respaldo de Netsparker
* [Equipo rojo](https://github.com/yeyintminthuhtut/Awesome-Red-Teaming)
* [SecLists] (https://github.com/danielmiessler/SecLists): listas útiles relacionadas con la seguridad para hacer referencia/trabajar en un pentest
* [Conversaciones de seguridad] (https://github.com/PaulSec/awesome-sec-talks)
* [Seguridad](https://github.com/sbilly/awesome-security)
* [Starting Up Security](https://scrty.io/): una colección de ensayos y enlaces de seguridad de la información para ayudar a los equipos en crecimiento a administrar los riesgos.
* [Inteligencia de amenazas] (https://github.com/hslatman/awesome-threat-intelligence)
* [Seguridad web](https://github.com/qazbnm456/awesome-web-security)
* [YARA](https://github.com/InQuest/awesome-yara)

#### Bases de conocimiento
* [0día](http://0día.hoy/)
* [Alienvault Open Threat Exchange (OTX)](https://otx.alienvault.com/) - Transmisión de amenazas en vivo.
* [Cvedetalles](https://www.cvedetalles.com/)
* [CyBOK](https://www.cybok.org/knowledgebase/)
* [Explotar-db](https://www.exploit-db.com/)
* [Jetlib](https://sec.jetlib.com/)
* [MITRE ATT&CK](https://attack.mitre.org/tactics/enterprise/)
* [Mitre](http://cve.mitre.org/)
* [Nvd.nist.gov](https://nvd.nist.gov/download/nvd-rss-analyzed.xml)
* [Técnicas OSINT Intel](https://inteltechniques.com/)
* [Pared abierta] (https://www.openwall.com/lists/oss-security/)
* [Packetstormsecurity](https://packetstormsecurity.com/)
* [Rapid7](https://www.rapid7.com/db/)
* [Enfoque de seguridad](https://www.securityfocus.com/bid)
* [Seebug](https://www.seebug.org/)
* [Talos Intelligence](https://talosintelligence.com/) - Transmisión de amenazas en vivo.
* [Los 100 principales blogs y sitios web de seguridad cibernética] (https://blog.feedspot.com/cyber_security_blogs/)
* [Laboratorio de vulnerabilidad](https://www.vulnerability-lab.com)
* [Wpvulndb](https://wpscan.com/api)
* [Iniciativa de día cero] (https://www.iniciativa de día cero.com/advisories/published/)

### Herramientas OSINT utilizadas

#### Herramientas OSINT generales
* [AbuseIPDB](https://www.abuseipdb.com/) - Motor de búsqueda de direcciones IP o dominios en la lista negra.
* [AutoShun](https://riskanalytics.com/community/) - Repositorio público de direcciones IP maliciosas y otros recursos.
* [BadIPs](https://www.badips.com/) - Búsqueda en la lista negra en línea.
* [Lector de código de barras](https://online-barcode-reader.inliteresearch.com/) - Decodifica códigos de barras en C#, VB, Java, C\C++, Delphi, PHP y otros lenguajes.
* [Belati](https://github.com/aancw/Belati) - La navaja suiza tradicional para OSINT. Belati es una herramienta para recopilar datos públicos y documentos públicos del sitio web y otros servicios para fines OSINT.
* [Lista de prohibición de IP de defensa binaria] (https://www.binarydefense.com/banlist.txt) - Lista negra de IP pública.
* [Blocklist Ipsets](https://github.com/firehol/blocklist-ipsets) - Lista negra de IP pública.
* [Censys](https://censys.io/): recopila datos sobre hosts y sitios web a través de escaneos diarios de ZMap y ZGrab.
* [CloudFrunt](https://github.com/MindPointGroup/cloudfrunt): herramienta para identificar dominios de CloudFront mal configurados.
* [Combinar] (https://github.com/mlsecproject/combine): herramienta de recopilación de fuentes de inteligencia de amenazas de código abierto.
* [Creepy](https://github.com/ilektrojohn/creepy) - Herramienta OSINT de geolocalización.
* [Datasploit](https://github.com/DataSploit/datasploit): herramienta para realizar varias técnicas OSINT en nombres de usuario, direcciones de correo electrónico y dominios.
* [Dnsenum](https://github.com/fwaeytens/dnsenum/): secuencia de comandos de Perl que enumera la información de DNS de un dominio, intenta transferencias de zona, realiza un ataque de estilo de diccionario de fuerza bruta y luego realiza búsquedas inversas en el resultados.
* [Dnsmap](https://github.com/makefu/dnsmap/) - Mapeador de red DNS pasivo.
* [Dnsrecon](https://github.com/darkoperator/dnsrecon/) - Script de enumeración de DNS.
* [Dnstracer](http://www.mavetju.org/unix/dnstracer.php): determina de dónde obtiene su información un servidor DNS determinado y sigue la cadena de servidores DNS.
* [Dork-cli](https://github.com/jgor/dork-cli) - Herramienta de línea de comando Google dork.
* [emagnet](https://github.com/wuseman/EMAGNET) - Herramienta de piratería automatizada que encontrará bases de datos filtradas.
* [FindFrontableDomains](https://github.com/rvrsh3ll/FindFrontableDomains) - Herramienta multiproceso para encontrar dominios frontales.
* [GOSINT](https://github.com/Nhoya/gOSINT) - Herramienta OSINT con múltiples módulos y un extractor de telegramas.
* [Github-dorks](https://github.com/techgaun/github-dorks): herramienta CLI para escanear repositorios/organizaciones de github en busca de posibles fugas de información confidencial.
* [GooDork](https://github.com/k3170makan/GooDork) - Herramienta de Google dorking de línea de comando.
* [Google Jacking Database](https://www.exploit-db.com/google-hacking-database) - Base de datos de tontos de Google; puede usarse para reconocimiento.
* [Greynoise](https://greynoise.io/) - "Anti-Threat Intelligence" Greynoise caracteriza el ruido de fondo de Internet, para que el usuario pueda concentrarse en lo que realmente es importante.
* [InfoByIp](https://www.infobyip.com/ipbulklookup.php) - Herramienta de búsqueda masiva de dominios e IP.
* [Intrigue Core](https://github.com/intrigueio/intrigue-core): marco para el descubrimiento de superficies de ataque.
* [Machinae](https://github.com/hurricanelabs/machinae): herramienta OSINT multipropósito que utiliza fuentes de inteligencia de amenazas.
* [Maltego](https://www.maltego.com/) - Software propietario para inteligencia forense y código abierto, de Paterva.
* [Lista de dominios de malware] (http://www.malwaredomainlist.com/) - Busque y comparta URL maliciosos.
* [Herramientas OSINT de NetBootcamp](https://netbootcamp.org/osinttools/)
* [Marco OSINT] (https://osintframework.com/)
* [OpenRefine](https://github.com/OpenRefine): herramienta eléctrica gratuita y de código abierto para trabajar con datos desordenados y mejorarlos.
* [Orbit](https://github.com/s0md3v/Orbit): dibuja relaciones entre monederos criptográficos con rastreo recursivo del historial de transacciones.
* [OsintStalker](https://github.com/milo2012/osintstalker) - Script Python para Facebook y geolocalización OSINT.
* [Outwit](http://www.outwit.com) - Busque, tome y organice todo tipo de datos y medios de fuentes en línea.
* [PaGoDo](https://github.com/opsdisk/pagodo) - Herramienta pasiva y automatizada de Google dorking.
* [Passivedns-client](https://github.com/chrislee35/passivedns-client): biblioteca y herramienta de consulta para consultar varios proveedores de DNS pasivos.
* [Passivedns](https://github.com/gamelinux/passivedns): rastreador de red que registra todas las respuestas del servidor DNS para su uso en una configuración de DNS pasivo.
* [Photon](https://github.com/s0md3v/Photon) - Crawler diseñado para OSINT.
* [Pown Recon] (https://github.com/pownjs/recon): marco de reconocimiento de objetivos impulsado por la teoría de grafos.
* [QuickCode](https://quickcode.io/) - Entorno de análisis de datos de Python y R.
* [Raven](https://github.com/0x09AL/raven) - Herramienta de recopilación de información de LinkedIn.
* [Recon-ng](https://github.com/lanmaster53/recon-ng) - Marco de reconocimiento web completo escrito en Python.
* [SecApps Recon](https://secapps.com/tools/recon/): herramienta de recopilación de información y reconocimiento de objetivos e interfaz de usuario.
* [Spamcop](https://www.spamcop.net/bl.shtml) - Lista negra basada en IP.
* [Spamhaus](https://www.spamhaus.org/lookup/) - Búsqueda de lista negra en línea.
* [Spiderfoot](https://www.spiderfoot.net/) - Herramienta de automatización OSINT de código abierto con una interfaz de usuario web y visualizaciones de informes
* [ThreatCrowd](https://www.threatcrowd.org/) - Motor de búsqueda de amenazas.
* [ThreatTracker](https://github.com/michael-yip/ThreatTracker): rastreador IOC basado en Python.
* [Vcsmap](https://github.com/melvinsh/vcsmap): herramienta basada en complementos para escanear sistemas de control de versiones públicas en busca de información confidencial.
* [XRay](https://github.com/evilsocket/xray) - XRay es una herramienta para reconocimiento, mapeo y recopilación OSINT de redes públicas.
* [Zen](https://github.com/s0md3v/Zen) - Encuentra las direcciones de correo electrónico de los usuarios de Github.
* [malc0de DNSSinkhole](http://malc0de.com/bl/): lista de dominios que se han identificado como distribuidores de malware durante los últimos 30 días.
* [Base de datos malc0de] (http://malc0de.com/database/) - Base de datos de incidentes en la que se pueden realizar búsquedas.
* [pygreynoise](https://github.com/GreyNoise-Intelligence/pygreynoise) - Biblioteca Python Greynoise
* [sn0int](https://github.com/kpcyrd/sn0int) - Marco OSINT semiautomático y administrador de paquetes.
* [theHarvester](https://github.com/laramies/theHarvester) - Recolector de correo electrónico, subdominio y nombres de personas.
  
#### Búsqueda OSINT criptográfica
* [Abuso de Bitcoin](https://www.bitcoinabuse.com/) - Base de datos de billeteras asociadas con ransomware, chantajistas y fraude.
* [Bitcoin Who's Who] (https://bitcoinwhoswho.com/) - Base de datos de información de identificación conocida de las direcciones de bitcoin.
* [Blockchair](https://blockchair.com/) - Explorador de blockchain múltiple.
* [Wallet Explorer](https://www.walletexplorer.com/) - Encuentra todas las direcciones de bitcoin asociadas conocidas desde una única dirección conocida.
  
#### Búsqueda de registros gubernamentales
* [Blackbook](https://www.blackbookonline.info/index.html) - Punto de partida de registros públicos.
* [FOIA Search](https://www.foia.gov/search.html) - Portal de solicitud de información del gobierno.
* [PACER](https://pacer.uscourts.gov/) - Acceso público a los expedientes judiciales federales.
* [RECAP](https://www.courtlistener.com/recap/) - Versión gratuita de PACER. Incluye extensiones de navegador para Chrome y Firefox.
* [Validador de SSN](https://www.ssnvalidator.com/index.aspx): confirma números de seguridad social válidos.
  
#### Motores de búsqueda nacionales
  *Motores de búsqueda localizados por país.*

* [Alleba (Filipinas)](https://www.alleba.com/)
* [Baidu (China)](https://www.baidu.com/)
* [Eniro (Suecia)](https://www.eniro.se/)
* [Goo (Japón)](https://www.goo.ne.jp/)
* [Najdsi (Eslovenia)](http://www.najdi.si)
* [Naver (Corea del Sur)](https://www.naver.com/)
* [Onet.pl (Polonia)](https://www.onet.pl/)
* [Orange (Francia)](https://www.orange.fr/portail)
* [Parseek (Irán)](https://www.parseek.com/)
* [SAPO (Portugal)](https://www.sapo.pt/)
* [Search.ch (Suiza)](https://www.search.ch/)
* [Wala (Israel)] (https://www.walla.co.il/)
* [Yandex (Rusia)](https://yandex.com/)
  
#### Metabúsqueda
  *Motores de búsqueda menos conocidos y usados.*

* [Todo en uno](https://all-io.net/)
* [TodoInternet](https://www.todointernet.com/)
* [Herramientas electrónicas] (https://www.etools.ch/)
* [FaganFinder](https://www.faganfinder.com/)
* [Goofram](http://www.goofram.com)
* [Myallsearch](http://www.myallsearch.com)
* [Qwant](https://www.qwant.com/)
* [Sputtr](http://www.sputtr.com)
* [Trovando](http://www.trovando.it)
* [WebOasis](https://weboas.is/)
* [Zapmeta](https://www.zapmeta.com/)
* [iZito](https://www.izito.com/)

#### Motores de búsqueda de búsqueda visual y agrupación
  *Motores de búsqueda que raspan múltiples sitios (Google, Yahoo, Bing, Goo, etc.) al mismo tiempo y devuelven resultados.*

  * [Carrot2](https://search.carrot2.org/#/search/web) * Organiza los resultados de búsqueda por temas.
  * [Yippy](https://www.yippy.com/) * Buscar usando varias fuentes a la vez

#### Búsqueda de documentos y diapositivas
  *Busque datos ubicados en archivos PDF, documentos de Word, diapositivas de presentación y más.*

* [Autorstream](http://www.authorstream.com)
* [Buscar-pdf-doc](http://www.findpdfdoc.com)
* [PDF completo gratuito] (http://www.freefullpdf.com)
* [Base de datos de fugas en alta mar] (https://offshoreleaks.icij.org)
* [Motor de búsqueda de PDF](http://www.pdfsearchengine.info)
* [RESUMEN](https://www.courtlistener.com/recap/)
* [Scribd](https://www.scribd.com/)
* [SlideShare](https://www.slideshare.net/)
* [Slideworld](http://www.slideworld.com)
* [soPDF.com](http://www.sopdf.com)

#### Buscar en Pastebin
  * [Pastebin](https://pastebin.com/) - Pastebin es un sitio web donde puede almacenar cualquier texto en línea para compartirlo fácilmente.

#### Búsqueda de código
  *Buscar por código fuente del sitio web*

  * [NerdyData](https://www.nerdydata.com/) - Motor de búsqueda de código fuente.
  * [SearchCode](https://searchcode.com): ayuda a encontrar ejemplos reales de funciones, API y bibliotecas en más de 10 fuentes.

#### Búsqueda en tiempo real, búsqueda en redes sociales y herramientas generales de redes sociales
  * [Audiense](https://audiense.com/)
  * [Blazent](https://www.blazent.com/)
  * [Brandwatch](https://www.brandwatch.com)
  * [Búfer](https://buffer.com)
  * [Buzzsumo](https://buzzsumo.com/)
  * [Geocreepy](http://www.geocreepy.com)
  * [Geofeedia](https://geofeedia.com)
  * [Hootsuite](https://www.hootsuite.com/)
  * [Hashtatit](https://www.hashatit.com/)
  * [Clear](https://klear.com/)
  * [Kred](https://www.home.kred/)
  * [SproutSocial](https://sproutsocial.com/)
  * [Netvibes](https://www.netvibes.com/en)
  * [OpinionCrawl](http://www.opinioncrawl.com)
  * [CI rival](https://www.rivaliq.com)
  * [Analizador social RSS](https://chrome.google.com/webstore/detail/rss-social-analyzer/ncmajlpbfckecekfamgfkmckbpihjfdn?hl=en)
  * [SocialBakers](https://www.socialbakers.com/)
  * [SociaBlade](http://socialblade.com)
  * [Social DownORNot](http://social.downornot.com)
  * [Buscador social](https://www.social-searcher.com/)
  * [Etiqueta](https://tagboard.com)
  * [Refinería de reputación](https://reputationrefinery.com/)
  * [UVRX](http://www.uvrx.com/social.html)

#### Búsqueda en Twitter
* [Backtweets](http://backtweets.com)
* [Comprobación de seguidores falsos] (https://fakers.statuspeople.com)
* [Primer tuit](https://ctrlq.org/first)
* [Primer tuit](https://about.twitter.com/#i_intelligence)
* [Foller.me](https://foller.me/)
* [FollowCheck](http://followcheck.com)
* [Followerwonk](https://followerwonk.com/)
* [Huella geosocial](http://geosocialfootprint.com)
* [Geochirp](http://www.geochirp.com)
* [Gigatweeter](http://gigatweeter.com)
* [Señal de tierra] (https://www.groundsignal.com)
* [FelizGrumpy](https://www.happygrumpy.com)
* [Harvard TweetMap](http://worldmap.harvard.edu/tweetmap)
* [Hashtagify](https://hashtagify.me/)
* [Hashtags.org](https://www.hashtags.org/)
* [GestionarFlitter](https://www.manageflitter.com/)
* [Mentionmapp](https://mentionmapp.com/)
* [OneMillionTweetMap](https://onemilliontweetmap.com/)
* [Velocidad de rango] (https://rankspeed.com/)
* [Rifle](https://crowdriff.com/)
* [RiteTag](https://ritetag.com)
* [Horario Trino](https://warble.co)
* [Sentiment140](http://www.twittersentiment.appspot.com)
* [Hora de dormir](http://sleepingtime.org)
* [Social Bearing](https://socialbearing.com/)
* [TruFan](https://www.trufan.io/)
* [Espátula](http://spoonbill.io)
* [Chat de Twitter de TWUBS] (http://twubs.com/twitter-chats)
* [Tagdef](https://tagdef.com/en/)
* [Tinfoleak](https://tinfoleak.com)
* [Tendencias24](https://trends24.in/)
* [Mapa de tendencias] (https://www.trendsmap.com/)
* [TwChat](http://twchat.com)
* [Twazzup](http://new.twazzup.com/)
* [Etiqueta de tweet](https://www.tweet-tag.com/)
* [TweetArchivist](http://www.tweetarchivist.com)
* [TweetDeck](https://tweetdeck.twitter.com/)
* [TweetMap](https://www.omnisci.com/demos/tweetmap)
* [TweetMap](http://worldmap.harvard.edu/tweetmap)* [TweetPsych](http://tweetpsych.com)
* [TweetStats](http://www.tweetstats.com)
* [TweetTunnel](http://tweettunnel.com)
* [Tweetreach](https://tweetreach.com/)
* [Twellow](https://www.twellow.com/)
* [Tweriod](https://www.tweriod.com/)
* [Twiangulate](http://www.twiangulate.com/search/)
* [Twicsy](https://twicsy.com/)
* [Twilert](https://www.twilert.com/)
* [Twipho](http://www.twipho.net)
* [TwitRSS](https://twitrss.me)
* [Twitonomy](http://www.twitonomy.com)
* [Búsqueda avanzada de Twitter](https://twitter.com/search-advanced?lang=en)
* [Auditoría de Twitter](https://www.twitteraudit.com)
* [Horario de chat de Twitter] (https://www.tweetreports.com/twitter-chat-schedule/)
* [Búsqueda de Twitter] (https://twitter.com/explore)
* [Twitterfall](https://twitterfall.com/)
* [burrrd.](https://burrrd.com)
* [sigue](https://sigue.com)

#### Búsqueda en Facebook
  * [Pulso de Ágora](https://barometer.agorapulse.com/home)
  * [Commun.it](https://commun.it/)
  * [Extraer cara](https://le-tools.com/)
  * [Karma de la página de fans] (https://www.fanpagekarma.com/)
  * [Búsqueda en Facebook](https://www.facebook.com/help/821153694683665/)
  * [Herramienta de búsqueda de Facebook](https://netbootcamp.org/facebook.html)
  * [FaceLIVE](https://www.facelive.org)
  * [Fb-sleep-stats](https://github.com/sqren/fb-sleep-stats)
  * [Buscar mi ID de Facebook](https://findmyfbid.in)
  * [Buscar-ID.com](https://buscar-id.com)
  * [SearchIsBack](https://searchisback.com)
  * [Wallfux](https://clearinghouse.wallflux.com/)
  * [Informe de Facebook de Wolfram Alpha] (https://www.wolframalpha.com/input/?i=facebook+report)
  * [Búsqueda de Facebook de Zesty] (http://zesty.ca/facebook/)

#### Búsqueda de Instagram
  * [Hashtagify](https://hashtagify.me/hashtag/wandavision)
  * [Iconosquare](https://pro.iconosquare.com/)
  * [Picodash](https://www.picodash.com)
  * [SnapMap](https://snapmap.knightlab.com/)
  * [Rango social](https://socialrank.com/)
  * [Worldcam](http://worldc.am)

#### Búsqueda en Pinterest
  * [Pingroupie](https://pingroupie.com/)

#### Búsqueda en Reddit
  *Herramientas para ayudar a descubrir más sobre un usuario o subreddit de reddit.*

* [Imgur](https://imgur.com/search): el sitio web de alojamiento de imágenes más popular utilizado por redditors.
* [Mostly Harmless](http://kerrick.github.io/Mostly-Harmless/#features) - Mostly Harmless busca la página que está viendo actualmente para ver si se ha enviado a reddit.
* [Archivo de Reddit] (https://www.redditinvestigator.com/) - Archivos históricos de publicaciones de reddit.
* [Búsqueda de comentarios de Reddit] (https://redditcommentsearch.com/) - Analice a los usuarios de reddit por historial de comentarios.
* [Investigador de Reddit] (http://www.redditinvestigator.com): investiga el historial de un usuario de reddit.
* [Reddit Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb): mejora su experiencia de reddit.
* [Analizador de usuarios de Reddit](https://atomiks.github.io/reddit-user-analyser/) - analizador de cuentas de usuario de reddit.
* [Subreddits](http://subreddits.org) - Descubre nuevos subreddits.

#### Búsqueda de VKontakte
  *Realice varios OSINT en el sitio de redes sociales ruso VKontakte.*

* [Barkov.net](https://vk.barkov.net/)
* [Árbol de informes](http://dcpu.ru/vk_repost_tree.php)
* [Snradar](http://snradar.azurewebsites.net) - Buscar imágenes por hora y lugar en que fueron tomadas
* [Estadísticas sociales](http://socialstats.ru)
* [Cazador de objetivos](https://targethunter.ru/)
* [Registro de objetivos] (https://targetolog.com/)
* [Búsqueda en la comunidad VK](https://vk.com/communities)
* [VK Parser](http://vkparser.ru) - Una herramienta para buscar un público objetivo y clientes potenciales.
* [Búsqueda de personas de VK] (https://vk.com/people)
* [VK a RSS Appspot] (http://vk-to-rss.appspot.com/)
* [VK5](http://vk5.city4me.com)
* [Descripción](https://vk.com/app3046467)

#### Búsqueda de blogs
  * [BlogSearchEngine](http://www.blogsearchengine.org)
  * [Notey](https://www.notey.com/) - Motor de búsqueda de publicaciones de blog.
  * [Outbrain](https://www.outbrain.com/publishers/)
  * [Twingly](https://www.twingly.com/)

#### Comprobación de nombre de usuario
* [Comprobar nombres de usuario](https://checkusernames.com/)
* [Knowem](https://knowem.com/) - Busque un nombre de usuario en más de 500 redes sociales populares.
* [Linkedin2Username](https://gitlab.com/initstring/linkedin2username): raspador web que usa credenciales válidas de LinkedIn para armar una lista de empleados para una empresa específica.
* [Nombre Checkr](https://www.namecheckr.com/)
* [Comprobación de nombre] (https://namecheckup.com)
* [Nombre Chk](https://www.namechk.com/)
* [Búsqueda de usuario] (https://usersearch.org/index.php)

#### Investigaciones personales
* [192 (Reino Unido)](https://www.192.com/)
* [411 (EE. UU.)] (https://www.411.com/)
* [Alumni.net](https://www.alumni.net/)
* [Ascendencia](https://www.ancestry.com/)
* [Been Verified](https://www.beenverified.com/) - Buena precisión, búsqueda de personas pagadas.
* [CVGadget](https://www.cvgadget.com/)
* [Canadá411](https://www.canada411.ca/)
* [Cedro](https://cedar.buffalo.edu/AdServ/person-search.html)
* [Aplicación Charlie](https://www.detective.io/)
* [Compañeros de clase](https://www.classmates.com/)
* [CrunchBase](https://www.crunchbase.com/)
* [Dato 24-7](https://www.data247.c* [TweetPsych](http://tweetpsych.com)
* [TweetStats](http://www.tweetstats.com)
* [TweetTunnel](http://tweettunnel.com)
* [Tweetreach](https://tweetreach.com/)
* [Twellow](https://www.twellow.com/)
* [Tweriod](https://www.tweriod.com/)
* [Twiangulate](http://www.twiangulate.com/search/)
* [Twicsy](https://twicsy.com/)
* [Twilert](https://www.twilert.com/)
* [Twipho](http://www.twipho.net)
* [TwitRSS](https://twitrss.me)
* [Twitonomy](http://www.twitonomy.com)
* [Búsqueda avanzada de Twitter](https://twitter.com/search-advanced?lang=en)
* [Auditoría de Twitter](https://www.twitteraudit.com)
* [Horario de chat de Twitter] (https://www.tweetreports.com/twitter-chat-schedule/)
* [Búsqueda de Twitter] (https://twitter.com/explore)
* [Twitterfall](https://twitterfall.com/)
* [burrrd.](https://burrrd.com)
* [sigue](https://sigue.com)

#### Búsqueda en Facebook
  * [Pulso de Ágora](https://barometer.agorapulse.com/home)
  * [Commun.it](https://commun.it/)
  * [Extraer cara](https://le-tools.com/)
  * [Karma de la página de fans] (https://www.fanpagekarma.com/)
  * [Búsqueda en Facebook](https://www.facebook.com/help/821153694683665/)
  * [Herramienta de búsqueda de Facebook](https://netbootcamp.org/facebook.html)
  * [FaceLIVE](https://www.facelive.org)
  * [Fb-sleep-stats](https://github.com/sqren/fb-sleep-stats)
  * [Buscar mi ID de Facebook](https://findmyfbid.in)
  * [Buscar-ID.com](https://buscar-id.com)
  * [SearchIsBack](https://searchisback.com)
  * [Wallfux](https://clearinghouse.wallflux.com/)
  * [Informe de Facebook de Wolfram Alpha] (https://www.wolframalpha.com/input/?i=facebook+report)
  * [Búsqueda de Facebook de Zesty] (http://zesty.ca/facebook/)

#### Búsqueda de Instagram
  * [Hashtagify](https://hashtagify.me/hashtag/wandavision)
  * [Iconosquare](https://pro.iconosquare.com/)
  * [Picodash](https://www.picodash.com)
  * [SnapMap](https://snapmap.knightlab.com/)
  * [Rango social](https://socialrank.com/)
  * [Worldcam](http://worldc.am)

#### Búsqueda en Pinterest
  * [Pingroupie](https://pingroupie.com/)

#### Búsqueda en Reddit
  *Herramientas para ayudar a descubrir más sobre un usuario o subreddit de reddit.*

* [Imgur](https://imgur.com/search): el sitio web de alojamiento de imágenes más popular utilizado por redditors.
* [Mostly Harmless](http://kerrick.github.io/Mostly-Harmless/#features) - Mostly Harmless busca la página que está viendo actualmente para ver si se ha enviado a reddit.
* [Archivo de Reddit] (https://www.redditinvestigator.com/) - Archivos históricos de publicaciones de reddit.
* [Búsqueda de comentarios de Reddit] (https://redditcommentsearch.com/) - Analice a los usuarios de reddit por historial de comentarios.
* [Investigador de Reddit] (http://www.redditinvestigator.com): investiga el historial de un usuario de reddit.
* [Reddit Suite](https://chrome.google.com/webstore/detail/reddit-enhancement-suite/kbmfpngjjgdllneeigpgjifpgocmfgmb): mejora su experiencia de reddit.
* [Analizador de usuarios de Reddit](https://atomiks.github.io/reddit-user-analyser/) - analizador de cuentas de usuario de reddit.
* [Subreddits](http://subreddits.org) - Descubre nuevos subreddits.

#### Búsqueda de VKontakte
  *Realice varios OSINT en el sitio de redes sociales ruso VKontakte.*

* [Barkov.net](https://vk.barkov.net/)
* [Árbol de informes](http://dcpu.ru/vk_repost_tree.php)
* [Snradar](http://snradar.azurewebsites.net) - Buscar imágenes por hora y lugar en que fueron tomadas
* [Estadísticas sociales](http://socialstats.ru)
* [Cazador de objetivos](https://targethunter.ru/)
* [Registro de objetivos] (https://targetolog.com/)
* [Búsqueda en la comunidad VK](https://vk.com/communities)
* [VK Parser](http://vkparser.ru) - Una herramienta para buscar un público objetivo y clientes potenciales.
* [Búsqueda de personas de VK] (https://vk.com/people)
* [VK a RSS Appspot] (http://vk-to-rss.appspot.com/)
* [VK5](http://vk5.city4me.com)
* [Descripción](https://vk.com/app3046467)

#### Búsqueda de blogs
  * [BlogSearchEngine](http://www.blogsearchengine.org)
  * [Notey](https://www.notey.com/) - Motor de búsqueda de publicaciones de blog.
  * [Outbrain](https://www.outbrain.com/publishers/)
  * [Twingly](https://www.twingly.com/)

#### Comprobación de nombre de usuario
* [Comprobar nombres de usuario](https://checkusernames.com/)
* [Knowem](https://knowem.com/) - Busque un nombre de usuario en más de 500 redes sociales populares.
* [Linkedin2Username](https://gitlab.com/initstring/linkedin2username): raspador web que usa credenciales válidas de LinkedIn para armar una lista de empleados para una empresa específica.
* [Nombre Checkr](https://www.namecheckr.com/)
* [Comprobación de nombre] (https://namecheckup.com)
* [Nombre Chk](https://www.namechk.com/)
* [Búsqueda de usuario] (https://usersearch.org/index.php)

#### Investigaciones personales
* [192 (Reino Unido)](https://www.192.com/)
* [411 (EE. UU.)] (https://www.411.com/)
* [Alumni.net](https://www.alumni.net/)
* [Ascendencia](https://www.ancestry.com/)
* [Been Verified](https://www.beenverified.com/) - Buena precisión, búsqueda de personas pagadas.
* [CVGadget](https://www.cvgadget.com/)
* [Canadá411](https://www.canada411.ca/)
* [Cedro](https://cedar.buffalo.edu/AdServ/person-search.html)
* [Aplicación Charlie](https://www.detective.io/)
* [Compañeros de clase](https://www.classmates.com/)
* [CrunchBase](https://www.crunchbase.com/)
* [Dato 24-7](https://www.data247.cf-gigantes de internet)
  * [Oficina de Mejores Negocios] (https://www.bbb.org/)
  * [Bizeurope](http://www.bizeurope.com)
  * [Bloomberg](https://www.bloomberg.com/markets/stocks)
  * [Fuente comercial](https://www.ebsco.com/products/research-databases/business-source-complete)
  * [Oficina Van Dijk](https://www.bvdinfo.com/en-gb/)
  * [Investigación comercial canadiense] (https://www.canada.ca/en/services/business/research.html)
  * [Recurso comercial canadiense] (http://www.cbr.ca)
  * [Directorio de empresas de Europa Central y Oriental] (https://globaledge.msu.edu/global-resources/resource/1274)
  * [Registro de empresas en todo el mundo](https://www.sg.ch/recht/handelsregister-notariate.html)
  * [Recursos de investigación de empresas por país de forma comparable] (https://www.comparablemente.com)
  * [CompeteShark](https://competeshark.com/)
  * [Información corporativa](https://www.corporateinformation.com/)
  * [CrunchBase](https://www.crunchbase.com)
  * [EDGAR en línea](https://www.dfinsolutions.com/products/edgar-online)
  * [Europages](https://www.europages.co.uk/)
  * [Registro Europeo de Empresas](https://ebra.be/)
  * [Ezilon](http://www.ezilon.com)
  * [Factiva](https://global.factiva.com)
  * [Glassdoor](https://www.glassdoor.com/index.htm)
  * [borde global] (https://globaledge.msu.edu/)
  * [GuideStar](https://www.guidestar.org/)
  * [Aspiradoras](https://www.dnb.com/products/marketing-sales/dnb-hoovers.html)
  * [Cía. 5000](https://www.inc.com/inc5000)
  * [InstantLogoSearch](http://instantlogosearch.com)
  * [iEspionaje](https://www.ispionage.com/)
  * [Guía de conocimientos para el registro de empresas internacionales](https://www.icaew.com/library/subject-gateways/business-management/knowledge-guide-international-company-registration)
  * [Linkedin](https://www.linkedin.com)
  * [Registros Nacionales de Empresas](https://en.wikipedia.org/wiki/List_of_official_business_registers)
  * [Intelecto fusionado] (https://www.mergentintellect.com/)
  * [Fusión en línea] (https://www.mergentonline.com/login.php)
  * [Investigación de Morningstar] (http://library.morningstar.com)
  * [Notablist](https://www.notablist.com)
  * [Directorio Orbis](https://orbisdirectory.bvdinfo.com/version-20181213/OrbisDirectory/Companies/Login)
  * [empresas abiertas] (https://opencorporates.com)
  * [Búho](https://corp.owler.com/)
  * [Registros de empresas en el extranjero] (https://www.gov.uk/government/publications/overseas-registries/overseas-registries)
  * [Investigación de Plunkett] (http://www.plunkettresearchonline.com/Login.aspx)
  * [Scoot](https://www.scoot.co.uk/)
  * [SEMrush](https://www.semrush.com)
  * [Serpstat](https://serpstat.com)
  * [SpyFu](https://www.spyfu.com/)
  * [Forbes Global 2000] (https://www.forbes.com/global2000/)
  * [Bóveda](https://www.vault.com/)
  * [Xing](https://www.xing.com/)

#### Investigación de dominios e IP
  * [Accuranker](https://www.accuranker.com)
  * [ahrefs](https://ahrefs.com): una herramienta para la investigación de backlinks, investigación de tráfico orgánico, investigación de palabras clave, marketing de contenido y más.
  * [Alexa](http://www.alexa.com)
  * [Herramientas para webmasters de Bing](https://www.bing.com/webmasters/about)
  * [Construido con](https://construidocon.com/)
  * [Operaciones centrales](https://centralops.net/co/)
  * [Dedicado o no](http://dedicatedornot.com)
  * [DNSDumpster](https://dnsdumpster.com)
  * [Historial DNS](http://dnshistory.org)
  * [Cosas DNS](https://www.dnsstuff.com/)
  * [DNSViz](https://dnsviz.net/)
  * [Big Data de Dominio](https://domainbigdata.com/)
  * [Rastreador de dominio](https://domaincrawler.com/)
  * [Expediente de dominio](https://centralops.net/co/DomainDossier.aspx)
  * [Herramientas de dominio] (https://whois.domaintools.com/) - Búsqueda de Whois y datos históricos de dominio/IP.
  * [whois fácil] (https://www.easywhois.com)
  * [Exonera Tor](https://metrics.torproject.org/exonerator.html) - Una base de datos de direcciones IP que han sido parte de la red Tor. Responde a la pregunta de si se ejecutó un relé Tor en una dirección IP determinada en una fecha determinada.
  * [Seguir.net](https://seguir.net/)
  * [GraphyStories](https://app.graphystories.com/)
  * [HypeStat](https://hypestat.com/)
  * [Infosniper](https://www.infosniper.net/)
  * [intoDNS](https://intodns.com/)
  * [Comprobación de IP] (http://www.ipchecking.com)
  * [Ubicación de IP] (https://www.iplocation.net/)
  * [Geolocalización IP 2](http://ip2geolocalización.com)
  * [Ubicación de IP 2] (http://www.ip2location.com/demo.aspx)
  * [Huellas IPFinger](https://www.ipfingerprints.com/)
  * [IPVoid](https://www.ipvoid.com/) - Conjunto de herramientas de dirección IP.
  * [IntelliTamper](https://www.softpedia.com/get/Internet/Other-Internet-Related/IntelliTamper.shtml)
  * [Kloth](http://www.kloth.net/services/)
  * [Herramientas de red](https://network-tools.com/)
  * [Majestuoso](https://majestic.com)
  * [MaxMind](https://www.maxmind.com/en/home)
  * [MXToolbox](https://mxtoolbox.com/) - Herramienta de búsqueda de registros MX.
  * [Informe del sitio de Netcraft](https://sitereport.netcraft.com/)
  * [Perfilador de OpenLink](https://www.openlinkprofiler.org/)
  * [Explorador de enlaces](https://moz.com/link-explorer)
  * [PageGlimpse](http://www.pageglimpse.com)
  * [Pentest-Tools.com](https://pentest-tools.com/information-gathering/google-hacking)
  * [PhishStats](https://phishstats.info/)
  * [Pulsedive](https://pulsedive.com)
  * [Quantcast](https://www.quantcast.com)
  * [Brote rápido] (https://www.quicksprout.com)
  * [RedirectDetective](https://redirectdetective.com/)
  * [Búsqueda remota de DNS] (https://remote.12dt.com)
  * [Robtex](https://www.robtex.com)
  * [SecurityTrails](https://securitytrails.com/dns-trails): API para buscar registros DNS actuales e históricos, WHOIS actual e histórico, tecnologías utilizadas por los sitios y búsqueda whois de teléfono, correo electrónico, dirección, direcciones IP, etc.
  * [SEMrush](https://www.semrush.com)
  * [SEOTools para Excel](https://seotoolsforexcel.com/)
  * [Web similar] (https://www.similarweb.com): compare las estadísticas y análisis de tráfico de cualquier sitio web.
  * [PequeñasSEOTools](https://smallseotools.com/)
  * [StatsCrop](https://www.statscrop.com/)
  * [Squatm3gator](https://github.com/david3107/squatm3gator) - Enumera los dominios disponibles generados modificando el nombre de dominio original a través de diferentes técnicas de cybersquatting
  * [URLVoid](https://www.urlvoid.com/) - Analiza un sitio web a través de múltiples motores de listas negras y herramientas de reputación en línea para facilitar la detección de sitios web fraudulentos y maliciosos.
  * [Wappalyzer](https://www.wappalyzer.com/)
  * [WebMeUp](https://webmeup.com/)
  * [Informador del sitio web] (https://website.informer.com/)
  * [Cuál es mi dirección IP] (https://whatismyipaddress.com/)
  * [Quién.es](https://quién.es/) - Información whois del dominio.
  * [Quién es Arin en línea] (https://whois.arin.net/ui/)
  * [Quién aloja esto] (https://www.whoihostingthis.com/)
  * [Whoisología](https://whoisology.com)
  * [WhoIsRequest](https://whoisrequest.com/)
  * [w3snoop](https://webboar.com.w3snoop.com/)
  * [Verisign](https://dnssec-analyzer.verisignlabs.com/)
  * [ViewDNS.info](https://viewdns.info/)
  * [Obtienes Signal](https://www.yougetsignal.com/)

#### Descubrimiento e investigación de palabras clave
  * [Google Adwords](https://ads.google.com/home/#!/) - Obtenga estadísticas y datos de volumen de palabras clave mensuales.
  * [Google Trends](https://trends.google.com/trends/?geo=US): vea cuántos usuarios buscan palabras clave específicas.
  * [Descubrimiento de palabras clave](https://www.keyworddiscovery.com/)
  * [Espía de palabras clave](https://www.keywordspy.com/)
  * [Herramienta para palabras clave] (https://keywordtool.io/)
  * [Diccionario inverso de One Look] (https://www.onelook.com/reverse-dictionary.shtml)
  * [Soovle](https://soovle.com/)
  * [Ubersuggest](https://neilpatel.com/ubersuggest/)
  * [Seguidor de palabras] (https://www.wordtracker.com/)

#### Historial web y captura de sitio web
  * [Archivo.is](https://archivo.is/)
  * [Viudanegra](https://softbytelabs.com/wp/viudanegra/)
  * [Páginas cobradas] (http://www.cachedpages.com)
  * [Vista en caché] (https://cachedview.com/)
  * [Herramientas de dominio] (https://account.domaintools.com/log-in/)
  * [Wayback Machine](https://archive.org/web/web.php) - Explora la historia de un sitio web.
  * [Archivador de Wayback Machine](https://github.com/jsvine/waybackpack)

#### Búsqueda de imágenes
  * [Imágenes de Baidu] (https://image.baidu.com/)
  * [Imágenes de Bing](https://www.bing.com/images/)
  * [Flickr](https://flickr.com/)
  * [Imagen de Google](https://images.google.com)
  * [Gramfeed](http://www.gramfeed.com/)
  * [Proyecto de identificación de imágenes](https://www.imageidentify.com/)
  * [Image Raider] (https://infringement.report/api/raider-reverse-image-search/)
  * [KarmaDecay](http://karmadecay.com/)
  * [Búsqueda de imágenes de Lycos](https://search.lycos.com/)
  * [FotoBucket](https://app.photobucket.com/explore)
  * [Picsearch](https://www.picsearch.com/)
  * [PicTriev](http://www.pictriev.com/)
  * [TinEye](https://tineye.com) - Motor de búsqueda inversa de imágenes.
  * [Websta](https://websta.me/)
  * [Worldcam](http://www.worldc.am)
  * [Búsqueda de imágenes de Yahoo] (https://images.search.yahoo.com)
  * [Imágenes de Yandex] (https://www.yandex.com/images)

#### Análisis de imagen
  * [ExifTool](https://exiftool.org/)
  * [Ghiro](https://www.getghiro.org/)
  * [ImpulseAdventure](https://www.impulseadventure.com/photo/jpeg-snoop.html)
  * [Visor de metadatos de imágenes de Jeffreys] (http://exif.regex.info/exif.cgi)
  * [JPEGsnoop](https://github.com/ImpulseAdventure/JPEGsnoop)
  * [Metapicz](http://metapicz.com/#landing)

#### Supervisión web
  * [Alltop](https://alltop.com/)
  * [Awasu](https://awasu.com/)
  * [Puente.Leslibres](https://bridge.leslibres.org/)
  * [Puente.Suumitsu](https://bridge.suumitsu.eu/)
  * [ChangeDetect](https://www.changedetect.com/)
  * [Deltafeed](https://bitreading.com/deltafeed/)
  * [Feed43](https://feed43.com/)
  * [Alimentador](https://www.qsensei.com/)
  * [Feed Exileed](http://feed.exileed.com/)
  * [Creador de filtros de alimentación] (https://feed.janicek.co/)
  * [Feedly](https://feedly.com/)
  * [FeedReader](https://www.feedreader.com/)
  * [Buscar RSS] (https://fetchrss.com/)
  * [Flipboard](https://flipboard.com/)
  * [Seguir esa página] (https://www.seguir esa página.com/)
  * [Google Alerts](https://www.google.com/alerts) - Un servicio de notificación y detección de cambios de contenido.
  * [InfoMinder](https://app.infominder.com/webminder/)
  * [Mención](https://mention.com/es/)
  * [Netvibes](https://www.netvibes.com/en)
  * [Newsblur](https://newsblur.com/)
  * [OmeaReader](https://www.jetbrains.com/omea/reader/)
  * [OnWebChange](https://onwebchange.com/)
  * [Reeder](https://reederapp.com/)
  * [Puente RSS](https://bridge.suumitsu.eu)
  * [Lector de fuentes RSS](https://chrome.google.com/webstore/detail/rss-feed-reader/pnjaodmkngahhkoihejjehlcdlnohgmp)
  * [RSSMicro](http://www.rssmicro.com/)
  * [Motor de búsqueda RSS](https://ctrlq.org/rss/)
  * [Centro de búsqueda de RSS](https://www.rsssearchhub.com/)
  * [RSSOwl](https://www.rssowl.org/)
  * [Selfoss](https://selfoss.aditu.de/)
  * [Rompedor de silo](https://www.silobreaker.com/)
  * [Talkwalker](https://www.talkwalker.com/)
  * [El Viejo Lector](https://theoldreader.com/home)
  * [versionista](https://versionista.com/)
  * [visualización](https://visualping.io)
  * [Vigilante del sitio web] (https://www.aignes.com/index.htm)
  * [Vientos](https://winds.getstream.io/create-account)

#### Análisis de redes sociales
  * [Gephi](https://gephi.org)
  * [ORA](http://www.casos.cs.cmu.edu/projects/ora/software.php)
  * [Visualizador Centinela](https://fmsasg.com/)
  * [Escenarios de investigación visual](https://vis.occrp.org)
  * [Grupo Wynyard](https://www.wynyardgroup.com/)

#### Búsqueda y enumeración de DNS
  * [Amass](https://github.com/caffix/amass): la herramienta amass busca fuentes de datos de Internet, realiza una enumeración de subdominios de fuerza bruta, busca archivos web y utiliza el aprendizaje automático para generar conjeturas de nombres de subdominios adicionales. La resolución de nombres DNS se realiza en muchos servidores públicos, por lo que el servidor autorizado verá el tráfico proveniente de diferentes ubicaciones. Escrito en Go.

#### Herramientas de reconocimiento de red
* [ACLight](https://github.com/cyberark/ACLight) - Script para el descubrimiento avanzado de cuentas privilegiadas sensibles - incluye Shadow Admins.
* [BuiltWith](https://builtwith.com/) - Herramienta de búsqueda de tecnología para sitios web.
* [CloudFail](https://github.com/m0rtem/CloudFail): desenmascara las direcciones IP del servidor ocultas detrás de Cloudflare buscando registros de bases de datos antiguos y detectando DNS mal configurados.
* [LdapMiner](https://sourceforge.net/projects/ldapminer/) - Utilidad de enumeración LDAP multiplataforma.
* [Escaneo masivo] (https://github.com/robertdavidgraham/masscan): escáner de puerto TCP, arroja paquetes SYN de forma asincrónica, escaneando todo Internet en menos de 5 minutos.
* [Netdiscover](https://github.com/alexxy/netdiscover) - Herramienta de escaneo de red simple y rápida.
* [Pentest-Tools](https://pentest-tools.com/home) - Conjunto en línea de varias herramientas diferentes relacionadas con pentest.
* [Regla](https://github.com/sensepost/ruler) - Herramienta para interactuar remotamente con servidores Exchange.
* [Shodan](https://www.shodan.io/) - Base de datos que contiene información sobre todos los dominios accesibles en Internet obtenida a partir del escaneo pasivo.
* [Spyse](https://spyse.com/): servicios de investigación web que analizan todo Internet mediante OSINT para simplificar la investigación de la infraestructura y las superficies de ataque.
* [Spyse.py](https://github.com/zeropwn/spyse.py): contenedor de la API de Python y cliente de línea de comandos para las herramientas alojadas en spyse.com.
* [Sublist3r](https://github.com/aboul3la/Sublist3r) - Herramienta de enumeración de subdominios para probadores de penetración.
* [ldapsearch](https://linux.die.net/man/1/ldapsearch) - Utilidad de línea de comandos de Linux para consultar servidores LDAP.
* [nmap](https://nmap.org/) - Escáner de seguridad gratuito para exploración de redes y auditorías de seguridad.
* [pyShodan](https://github.com/GoVanguard/pyShodan): secuencia de comandos de Python 3 para interactuar con la API de Shodan (requiere una clave de API válida).
* [smbmap](https://github.com/ShawnDEvans/smbmap) - Práctica herramienta de enumeración SMB.
* [xprobe2](https://linux.die.net/man/1/xprobe2) - Herramienta de huellas dactilares del sistema operativo de código abierto.
* [zmap](https://zmap.io/): escáner de red de código abierto que permite a los investigadores realizar fácilmente estudios de red en toda Internet.
  

### Herramientas de recuperación de datos y enumeración de explotación


#### Pruebas de penetración Distribuciones de sistemas operativos
* [ArchStrike](https://archstrike.org/) - Repositorio Arch GNU/Linux para profesionales y entusiastas de la seguridad.
* [AttifyOS](https://github.com/adi0x90/attifyos): distribución de GNU/Linux centrada en herramientas útiles durante las evaluaciones de seguridad de Internet de las cosas (IoT).
* [BackBox](https://www.backbox.org/) - Distribución basada en Ubuntu para pruebas de penetración y evaluaciones de seguridad.
* [BlackArch](https://www.blackarch.org/) - Distribución basada en Arch GNU/Linux para probadores de penetración e investigadores de seguridad.
* [Buscador](https://inteltechniques.com/buscador/) - Máquina virtual GNU/Linux preconfigurada para investigadores en línea.
* [Laboratorio de seguridad de Fedora](https://labs.fedoraproject.org/en/security/): proporciona un entorno de prueba seguro para trabajar en auditorías de seguridad, análisis forense, rescate de sistemas y enseñanza de metodologías de pruebas de seguridad.
* [Kali](https://www.kali.org/) - Distribución GNU/Linux diseñada para análisis forense digital y pruebas de penetración.
* [Kit de herramientas de seguridad de red (NST)] (https://networksecuritytoolkit.org/nst/index.html): sistema operativo en vivo de arranque basado en Fedora diseñado para proporcionar un fácil acceso a las mejores aplicaciones de seguridad de red de código abierto.
* [Parrot Security OS](https://www.parrotsec.org/) - Distribución similar a Kali usando los mismos repositorios, pero con características adicionales como Tor e integración I2P.
* [The Pentesters Framework] (https://github.com/trustedsec/ptf): distribución organizada en torno al estándar de ejecución de pruebas de penetración (PTES), que proporciona una colección seleccionada de utilidades que elimina las cadenas de herramientas que a menudo no se usan.

#### Marcos multiparadigmáticos
  * [Armitage](http://www.fastandeasyhacking.com/) - Interfaz gráfica de usuario basada en Java para Metasploit Framework.
  * [AutoSploit](https://github.com/NullArray/AutoSploit): explotador masivo automatizado, que recopila el objetivo empleando la API de Shodan.io y elige mediante programación los módulos de explotación de Metasploit en función de la consulta de Shodan.
  * [Faraday](https://github.com/infobyte/faraday): entorno de pentesting integrado multiusuario para equipos rojos que realizan pruebas de penetración cooperativas, auditorías de seguridad y evaluaciones de riesgos.
  * [Habu Hacking Toolkit](https://github.com/fportantier/habu): conjunto unificado de herramientas que abarca reconocimiento pasivo, ataques a la red, monitoreo de redes sociales y huellas digitales de sitios web.
  * [Mad-Metasploit](https://www.hahwul.com/p/mad-metasploit.html) - Scripts adicionales para Metasploit.
  * [Metasploit](https://www.metasploit.com/): software para equipos de seguridad ofensivos para ayudar a verificar vulnerabilidades y administrar evaluaciones de seguridad.
  * [Marco de seguridad móvil (MobSF)](https://github.com/MobSF/Mobile-Security-Framework-MobSF/) - Marco de pentesting de aplicaciones móviles automatizado capaz de análisis estático, análisis dinámico, análisis de malware y pruebas de API web .
  * [Pupy](https://github.com/n1nj4sec/pupy) - Herramienta multiplataforma (Windows, Linux, macOS, Android) de administración remota y posexplotación.
  * [Ruptura](https://github.com/dionyziz/rupture) - Herramienta multipropósito capaz de ataques man-in-the-middle, ataques BREACH y otros ataques criptográficos basados ​​en compresión.

#### Escáneres de vulnerabilidad de red
  * [Nessus](https://www.tenable.com/products/nessus/nessus-professional): escáner de vulnerabilidad de red comercial.
  * [Nexpose](https://www.rapid7.com/products/nexpose/): motor comercial de evaluación de gestión de riesgos y vulnerabilidades que se integra con Metasploit, vendido por Rapid7.
  * [OpenVAS](https://www.openvas.org/) - Implementación de código abierto del popular sistema de evaluación de vulnerabilidades Nessus.
  * [Vuls](https://github.com/future-architect/vuls) - Escáner de vulnerabilidades de Linux/FreeBSD sin agente escrito en Go.

#### Escáneres de vulnerabilidades web
  * [ACSTIS](https://github.com/tijme/angularjs-csti-scanner) - Detección automatizada de inyección de plantilla del lado del cliente (escape/bypass de sandbox) para AngularJS.
  * [Burp Suite](https://portswigger.net/burp) - Escáner comercial de vulnerabilidades web, con edición comunitaria limitada.
  * [cms-explorer](https://code.google.com/archive/p/cms-explorer/): revela los módulos, complementos, componentes y temas específicos que se ejecutan en varios sitios web con sistemas de administración de contenido.
  * [Escáner de seguridad de aplicaciones web Netsparker] (https://www.netsparker.com/): escáner de seguridad de aplicaciones web comerciales para encontrar automáticamente muchos tipos diferentes de fallas de seguridad.
  * [Nikto](https://cirt.net/nikto2) - Servidor web de caja negra ruidoso pero rápido y escáner de vulnerabilidad de aplicaciones web.
  * [Observatorio](https://observatory.mozilla.org/) - Utilidad gratuita de escaneo web en línea.
  * [OWASP Zed Attack Proxy (ZAP)](https://owasp.org/www-project-zap/) - Fuzzer y proxy de interceptación HTTP programable y rico en funciones para aplicaciones web de pruebas de penetración.
  * [Encabezados de seguridad](https://securityheaders.com/): utilidad en línea gratuita para verificar los encabezados HTTP de un sitio web en busca de vulnerabilidades de seguridad.
  * [SQLmate](https://github.com/s0md3v/sqlmate): un amigo de sqlmap que identifica las vulnerabilidades de sqli en función de un idiota y un sitio web determinados (opcional).
  * [WPScan](https://wpscan.com/wordpress-security-scanner) - Escáner de vulnerabilidades de WordPress de caja negra.

#### Explotación web
  * [Browser Exploitation Framework (BeEF)](https://github.com/beefproject/beef) - Servidor de comando y control para entregar exploits a navegadores web requisados.
  * [Commix](https://github.com/commixproject/commix): herramienta automatizada de inyección y explotación de comandos del sistema operativo todo en uno.
  * [Drupwn](https://github.com/immunIT/drupwn/) - Herramienta de explotación de aplicaciones web de Drupal.
  * [EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness): herramienta para tomar capturas de pantalla de sitios web, proporcionar información de encabezado del servidor e identificar las credenciales predeterminadas si es posible.
  * [fimap](https://github.com/kurobeats/fimap): busque, prepare, audite, explote e incluso Google automáticamente para detectar errores de LFI/RFI.
  * [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - Diccionario de patrones de ataque y primitivos para caja negrainyección de fallas en la aplicación y descubrimiento de recursos.
  * [IIS-Shortname-Scanner](https://github.com/irsdl/IIS-ShortName-Scanner): herramienta de línea de comandos para explotar la vulnerabilidad de divulgación de información de tilde de Windows IIS.
  * [Kadabra](https://github.com/D35m0nd142/Kadabra) - Explorador y explorador LFI automático.
  * [Kadimus](https://github.com/P0cL4bs/Kadimus) - Herramienta de exploración y explotación de LFI.
  * [LFISuite](https://github.com/D35m0nd142/LFISuite): una herramienta diseñada para explotar las vulnerabilidades de inclusión de archivos locales.
  * [libformatstr](https://github.com/hellman/libformatstr) - Script de Python diseñado para simplificar las explotaciones de cadenas de formato.
  * [liffy](https://github.com/hvqzao/liffy) - Herramienta de explotación de LFI.
  * [lyncsmash](https://github.com/nyxgeek/lyncsmash): una colección de herramientas para enumerar y atacar las instalaciones autohospedadas de Skype for Business y Microsoft Lync
  * [NoSQLmap](https://github.com/codingo/NoSQLMap) - Herramienta automática de inyección de NoSQL y adquisición de base de datos.
  * [SQLmap](http://sqlmap.org/) - Herramienta automatizada de inyección de SQL y adquisición de base de datos.
  * [sqlninja](http://sqlninja.sourceforge.net/) - Herramienta automatizada de inyección de SQL y toma de control de la base de datos.
  * [sslstrip2](https://github.com/LeonardoNve/sslstrip2) - Versión SSLStrip para derrotar a HSTS.
  * [sslstrip](https://github.com/moxie0/sslstrip) - Demostración de los ataques de eliminación de HTTPS.
  * [tplmap](https://github.com/epinna/tplmap): inyección automática de plantillas del lado del servidor y herramienta de toma de control del servidor web.
  * [VHostScan] (https://github.com/codingo/VHostScan): un escáner de host virtual que realiza búsquedas inversas, se puede usar con herramientas dinámicas, detecta escenarios generales, alias y páginas predeterminadas dinámicas.
  * [wafw00f](https://github.com/EnableSecurity/wafw00f): identifica y toma huellas digitales de productos de firewall de aplicaciones web (WAF).
  * [webscreenshot](https://github.com/maaaaz/webscreenshot): un script simple para tomar capturas de pantalla de una lista de sitios web.
  * [weevely3](https://github.com/epinna/weevely3) - Shell web armado.
  * [Wordpress Exploit Framework](https://github.com/rastating/wordpress-exploit-framework): marco Ruby para desarrollar y usar módulos que ayudan en las pruebas de penetración de sitios web y sistemas impulsados ​​por WordPress.
  * [WPSploit](https://github.com/espreto/wpsploit) - Explota sitios web potenciados por WordPress con Metasploit.

#### Herramientas de red
  * [dnstwist](https://github.com/elceef/dnstwist): motor de permutación de nombres de dominio para detectar errores tipográficos, phishing y espionaje corporativo.
  * [dsniff](https://www.monkey.org/~dugsong/dsniff/) - Colección de herramientas para auditoría de red y pentesting.
  * [enumdb](https://github.com/m8r0wn/enumdb) - Utilidad de fuerza bruta de MySQL y MSSQL
  * [FireAway](https://github.com/tcstool/Fireaway/) - Herramienta de auditoría de cortafuegos y omisión de seguridad.
  * [impacket](https://github.com/SecureAuthCorp/impacket) - Colección de clases de Python para trabajar con protocolos de red.
  * [Intercepter-NG](http://sniff.su/) - Juego de herramientas de red multifuncional.
  * [kerbrute](https://github.com/ropnop/kerbrute): una herramienta para realizar fuerza bruta previa a la autenticación de Kerberos.
  * [Cañón de iones de órbita baja (LOIC)] (https://github.com/NewEraCracker/LOIC/): herramienta de prueba de estrés de red de código abierto.
  * [Ncat](https://nmap.org/ncat/) - Utilidad de línea de comandos TCP/IP compatible con múltiples protocolos.
  * [netcut](https://arcai.com/netcut/) - Utilidad basada en ARP para descubrir y falsificar direcciones MAC y habilitar/deshabilitar la conectividad de red en dispositivos de red.
  * [Network-Tools.com](https://network-tools.com/) - Sitio web que ofrece una interfaz para numerosas utilidades de red básicas como `ping`, `traceroute`, `whois` y más.
  * [patator](https://github.com/lanjelot/patator) - Patator es un juego de fuerza bruta polivalente, con un diseño modular y un uso flexible.
  * [pig](https://github.com/rafael-santiago/pig) - Herramienta de elaboración de paquetes GNU/Linux.
  * [Praeda](http://h.foofus.net/?page_id=218) - Recolector de datos de impresora multifunción automatizado para recopilar datos utilizables durante las evaluaciones de seguridad.
  * [Kit de herramientas de explotación de impresoras (PRET)] (https://github.com/RUB-NDS/PRET): herramienta para pruebas de seguridad de impresoras con conectividad IP y USB, fuzzing y explotación del lenguaje de impresora PostScript, PJL y PCL caracteristicas.
  * [routersploit](https://github.com/threat9/routersploit): marco de explotación de código abierto similar a Metasploit pero dedicado a dispositivos integrados.
  * [scapy](https://github.com/secdev/scapy) - Biblioteca y programa interactivo de manipulación de paquetes basado en Python.
  * [Sockstress](https://github.com/defuse/sockstress) - Utilidad DoS basada en TCP.
  * [SPARTA](https://sparta.secforce.com/): interfaz gráfica que ofrece acceso programable y configurable a herramientas de enumeración y escaneo de infraestructura de red existente.
  * [Spyse](https://spyse.com/): servicios de investigación web que analizan todo Internet mediante OSINT para simplificar la investigación de la infraestructura y las superficies de ataque.
  * [Spyse.py](https://github.com/zeropwn/spyse.py) - API de Python wrapero y cliente de línea de comandos para las herramientas alojadas en spyse.com.
  * [THC Hydra](https://github.com/vanhauser-thc/thc-hydra): herramienta de descifrado de contraseñas en línea con soporte integrado para muchos protocolos de red, incluidos HTTP, SMB, FTP, telnet, ICQ, MySQL, LDAP, IMAP, VNC y más.
  * [UFONet](https://github.com/epsylon/ufonet/) - Herramienta DDoS/DoS de capa 7.
  * [Zarp](https://github.com/hatRiot/zarp/) - Herramienta de ataque de red multipropósito, tanto por cable como inalámbrica.

#### Analizadores de protocolos y sniffers
  * [tcpdump/libpcap](https://www.tcpdump.org/) - Analizador de paquetes común que se ejecuta bajo la línea de comandos.
  * [Wireshark](https://www.wireshark.org/) - Analizador de protocolo de red multiplataforma gráfico ampliamente utilizado.
  * [Yersinia](https://tools.kali.org/vulnerability-analysis/yersinia) - Analizador de paquetes y protocolos con capacidad MITM.
  * [Fiddler](https://www.telerik.com/fiddler) - Herramienta de captura de paquetes multiplataforma para capturar tráfico HTTP/HTTPS.
  * [netsniff-ng](https://github.com/netsniff-ng/netsniff-ng) - Navaja suiza para rastrear redes Linux.
  * [Dshell](https://github.com/USArmyResearchLab/Dshell) - Marco de análisis forense de red.
  * [Chaosreader](http://chaosreader.sourceforge.net/) - Herramienta universal de rastreo de TCP/UDP que descarga datos de sesión de varios protocolos.

#### Proxies y herramientas MITM
  * [BetterCAP](https://www.bettercap.org/) - Marco MITM modular, portátil y fácilmente extensible.
  * [dnschef](https://github.com/iphelix/dnschef) - Proxy DNS altamente configurable para pentesters.
  * [Ettercap](https://www.ettercap-project.org/) - Paquete completo y maduro para ataques de máquina en el medio.
  * [evilgrade] (https://github.com/infobyte/evilgrade): marco modular para aprovechar las implementaciones de actualización deficientes mediante la inyección de actualizaciones falsas.
  * [mallory](https://github.com/justmao945/mallory) - Proxy HTTP/HTTPS sobre SSH
  * [MITMf](https://github.com/byt3bl33d3r/MITMf) - Marco multipropósito man-in-the-middle.
    - p.ej. `mitmf --arp --spoof -i eth0 --gateway 192.168.1.1 --targets 192.168.1.20 --inject --js-url http://192.168.1.137:3000/hook.js`
  * [mitmproxy](https://github.com/mitmproxy/mitmproxy): proxy HTTP de intercepción compatible con TLS interactivo para probadores de penetración y desarrolladores de software.
  * [Morpheus](https://github.com/r00t-3xp10it/morpheus) - Herramienta automatizada de secuestro TCP/IP de ettercap.
  * [Responder-Windows](https://github.com/lgandx/Responder-Windows): versión de Windows del envenenador NBT-NS/LLMNR/MDNS anterior.
  * [Respondedor](https://github.com/lgandx/Responder): envenenador NBT-NS, LLMNR y MDNS de código abierto.
  * [SSH MITM](https://github.com/jtesta/ssh-mitm) - Interceptar conexiones SSH con un proxy; todas las contraseñas y sesiones de texto sin formato se registran en el disco.

#### Herramientas de red inalámbrica
  * [Aircrack-ng](https://www.aircrack-ng.org/) - Conjunto de herramientas para auditar redes inalámbricas.
  * [BetterCAP](https://www.bettercap.org/) - Wifi, Bluetooth LE y reconocimiento HID y marco de ataque MITM, escrito en Go.
  * [Fluxion](https://github.com/FluxionNetwork/fluxion) - Conjunto de ataques WPA automatizados basados ​​en ingeniería social.
  * [Kismet](https://www.patreon.com/kismetwireless): herramienta de descubrimiento de redes inalámbricas.
  * [Kit de herramientas MANA] (https://github.com/sensepost/mana) - Rogue AP y utilidad man-in-the-middle.
  * [NetStumbler](https://www.netstumbler.com/downloads/) - Herramienta de escaneo WLAN.
  * [WiFi Pumpkin](https://github.com/P0cL4bs/wifipumpkin3) - Todo en una utilidad de explotación y suplantación de Wi-Fi.
  * [wifi-pickle](https://github.com/GoVanguard/wifi-pickle) - Ataques de puntos de acceso falsos.
  * [Wifite](https://github.com/derv82/wifite) - Herramienta de ataque inalámbrica automatizada.
  
#### Herramientas de seguridad de la capa de transporte
  * [tlssled](https://tools.kali.org/information-gathering/tlssled) - Conjunto completo de pruebas de TLS/SSL.
  * [SSLscan](https://github.com/rbsec/sslscan) - Analizador SSL/TLS de línea de comando rápido.
  * [SSLyze](https://github.com/nabla-c0d3/sslyze): analizador de configuración TLS/SSL rápido y completo para ayudar a identificar errores de configuración de seguridad.
  * [SSL Labs](https://www.ssllabs.com/ssltest/) - Conjunto de pruebas de TLS/SSL en línea para revelar versiones y cifrados de TLS/SSL compatibles.
  * [crackpkcs12](https://github.com/crackpkcs12/crackpkcs12): programa multiproceso para descifrar archivos PKCS#12 (extensiones `.p12` y `.pfx`), como certificados TLS/SSL.
  * [spoodle](https://github.com/avicoder/spoodle) - Subdominio masivo + escáner de vulnerabilidad POODLE.
  * [SMTP TLS Checker](https://luxsci.com/smtp-tls-checker) - Conjunto de pruebas TLS/SSL en línea para servidores SMTP.
  
#### Criptografía
  * [FeatherDuster](https://github.com/nccgroup/featherduster) - Herramienta de análisis para descubrir fallas en la criptografía.
  * [rsatool](https://github.com/ius/rsatool) - Herramienta para calcular parámetros RSA y RSA-CRT.
  * [xortool](https://github.com/hellman/xortool/) - Herramienta de análisis de cifrado XOR.

#### Posterior a la explotación
* [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec/) - Post-explotación multipropósitoen suite que contiene muchos complementos.
* [DBC2](https://github.com/Arno0x/DBC2/) - Herramienta de post-explotación multipropósito.
* [Empire](https://github.com/EmpireProject/Empire/) - Marco de post-explotación basado en PowerShell (Windows) y Python (Linux/OS X).
* [EvilOSX](https://github.com/Marten4n6/EvilOSX/) - puerta trasera de macOS compatible con docker.
* [Insondable](https://github.com/xor-function/fathomless): una colección de herramientas posteriores a la explotación para sistemas Linux y Windows.
* [FruityC2](https://github.com/xtr4nge/FruityC2/): marco de posexplotación basado en agentes y de código abierto con una interfaz de usuario web para la administración.
* [Koadic](https://github.com/zerosum0x0/koadic): rootkit posterior a la explotación de Windows, que utiliza principalmente Windows Script Host.
* [PlugBot](https://www.redteamsecure.com/research/plugbot-hardware-botnet-research): se puede instalar en un dispositivo ARM para uso de comando y control y más.
* [Portia](https://github.com/milo2012/portia) - Herramienta automatizada posterior a la explotación para movimiento lateral y escalada de privilegios.
* [ProcessHider](https://github.com/M00nRise/ProcessHider/) - Herramienta posterior a la explotación para ocultar procesos.
* [Pupy](https://github.com/n1nj4sec/pupy/) - Herramienta de posexplotación multiplataforma de código abierto, escrita principalmente en Python.
* [RemoteRecon](https://github.com/xorrior/RemoteRecon/) - Utilidad posterior a la explotación que utiliza múltiples agentes para realizar diferentes tareas.
* [TheFatRat](https://github.com/Exploit-install/TheFatRat) - Herramienta diseñada para generar troyanos de acceso remoto (puertas traseras) con msfvenom.arch-project/) - Se puede instalar en un dispositivo ARM para Command & Control uso y más.
* [p0wnedShell](https://github.com/Cn33liz/p0wnedShell): utilidad de posexplotación basada en PowerShell que utiliza .NET.
* [poet](https://github.com/offlinemark/poet) - Herramienta de post-explotación simple pero multipropósito.

#### Herramientas de exfiltración
  * [Kit de herramientas de exfiltración de datos (DET)](https://github.com/PaulSec/DET): prueba de concepto para realizar la exfiltración de datos utilizando uno o varios canales al mismo tiempo.
  * [dnsteal](https://github.com/m57/dnsteal/) - Servidor DNS falso para extraer archivos sigilosamente.
  * [HTTPTunnel](https://github.com/larsbrinkhoff/httptunnel) - Túnel de datos a través de solicitudes HTTP GET/POST puras.
  * [Iodine](https://github.com/yarrick/iodine) - Túnel de datos IPv4 a través de un servidor DNS; útil para la exfiltración de redes donde el acceso a Internet está protegido por firewall, pero se permiten consultas de DNS.
  * [MailSniper](https://github.com/dafthack/MailSniper): busque en el correo electrónico en un entorno de Microsoft Exchange términos específicos (contraseñas, información privilegiada, información de arquitectura de red, etc.).
  * [mallory](https://github.com/justmao945/mallory) - Proxy HTTP/HTTPS sobre SSH.
  * [mimikatz](https://blog.gentilkiwi.com/mimikatz) - Herramienta de extracción de credenciales para el sistema operativo Windows.
  * [mimikittenz](https://github.com/orlyjamie/mimikittenz) - Herramienta PowerShell posterior a la explotación para extraer datos de la memoria del proceso.
  * [PANHunt](https://github.com/Dionach/PANhunt) - Buscar sistemas de archivos para tarjetas de crédito.
  * [PassHunt](https://github.com/Dionach/PassHunt) - Buscar sistemas de archivos para contraseñas.
  * [ptunnel-ng](https://github.com/lnslbrty/ptunnel-ng) - Túnel de tráfico IPv4 a través de pings ICMP; lento pero sigiloso cuando el tráfico de exfiltración de IP normal está bloqueado.
  * [pwnat](https://github.com/samyk/pwnat) - Perfora agujeros en cortafuegos y NAT.
  * [spYDyishai](https://github.com/Night46/spYDyishai/) - Herramienta local de exfiltración de credenciales de Google, escrita en Python.
  * [tgcd](http://tgcd.sourceforge.net/) - Utilidad de red Unix simple para ampliar la accesibilidad de los servicios de red basados ​​en TCP/IP más allá de los cortafuegos.

#### Analizadores estáticos
  * [Androbugs-Framework](https://github.com/AndroBugs/AndroBugs_Framework/) - Herramienta de análisis de vulnerabilidad de programas Android.
  * [Androwarn](https://github.com/maaaaz/androwarn/) - Herramienta de análisis de código estático de Android.
  * [APKinspector](https://github.com/honeynet/apkinspector/) - Herramienta de análisis de APK de Android con GUI.
  * [bandit](https://pypi.org/project/bandit/) - Analizador estático orientado a la seguridad para código python.
  * [Brakeman](https://github.com/presidentbeef/brakeman) - Escáner de vulnerabilidades de seguridad de análisis estático para aplicaciones Ruby on Rails.
  * [Codebeat (código abierto)](https://codebeat.co/open-source/) - Implementación de código abierto de la herramienta comercial de análisis de código estático con integración de GitHub.
  * [Codelyzer](https://github.com/mgechev/codelyzer): un conjunto de reglas tslint para el análisis de código estático de proyectos Angular TypeScript. Puede ejecutar el analizador de código estático en aplicaciones web, NativeScript, Ionic, etc.
  * [cppcheck](http://cppcheck.sourceforge.net/) - Analizador estático C/C++ extensible enfocado en encontrar errores.
  * [FindBugs](http://findbugs.sourceforge.net/) - Analizador estático de software gratuito para buscar errores en el código Java.
  * [Icewater](https://github.com/SupportIntelligence/Icewater) - 16 432 reglas gratuitas de Yara.
  * [Evaluación conjunta de defensa avanzada para la aplicación de Androidions (JAADAS)](https://github.com/flankerhqd/JAADAS/) - Herramienta multipropósito de análisis estático de Android.
  * [Comprobación de dependencias de OWASP](https://owasp.org/www-project-dependency-check/): herramienta de análisis estático de código abierto que enumera las dependencias utilizadas por el código de software Java y .NET (con soporte experimental para Python, Ruby, Node.js, C y C++) y enumera las vulnerabilidades de seguridad asociadas con las dependencias.
  * [pefile](https://github.com/erocarrera/pefile) - Inspector de archivos ejecutables portátiles estáticos.
  * [Progpilot](https://github.com/designsecurity/progpilot) - Herramienta de análisis de seguridad estática para código PHP.
  * [Kit de revisión rápida de Android (Qark)] (https://github.com/linkedin/qark/): herramienta para encontrar vulnerabilidades de aplicaciones de Android relacionadas con la seguridad.
  * [ShellCheck](https://github.com/koalaman/shellcheck) - Herramienta de análisis de código estático para script de shell.
  * [smalisca](https://github.com/dorneanu/smalisca) - Herramienta de análisis de código estático de Android.
  * [sobelow](https://github.com/nccgroup/sobelow) - Análisis estático centrado en la seguridad para Phoenix Framework.
  * [truffleHog](https://github.com/dxa4481/truffleHog) - Escáner de repositorio Git.
  * [Veracode](https://www.veracode.com/) - Plataforma de nube comercial para análisis de código estático, análisis de código dinámico, análisis de dependencia/complemento y más.
  * [VisualCodeGrepper](https://github.com/nccgroup/VCG): herramienta de análisis de código estático de código abierto compatible con Java, C, C++, C#, PL/SQL, VB y PHP. VisualCodeGrepper también cumple con las mejores prácticas de OWASP.
  * [Yara](https://github.com/VirusTotal/yara) - Herramienta de análisis de patrones estáticos para investigadores de malware.

#### Analizadores dinámicos
  * [AndroidHooker](https://github.com/AndroidHooker/hooker/) - Herramienta dinámica de análisis de aplicaciones Android.
  * [Androl4b](https://github.com/sh4hin/Androl4b/): máquina virtual de seguridad de Android basada en Ubuntu-MATE para ingeniería inversa y análisis de malware.
  * [Cheat Engine](https://www.cheatengine.org/) - Depurador de memoria y editor hexadecimal para ejecutar aplicaciones.
  * [ConDroid](https://github.com/JulianSchuette/ConDroid) - Herramienta de análisis de aplicaciones dinámicas de Android.
  * [Cuckoo] (https://github.com/cuckoosandbox): herramienta de análisis de malware dinámica automatizada.
  * [DECAF](https://github.com/decicaf-project/DECAF) - Herramienta de análisis de código dinámico.
  * [droidbox](https://github.com/pjlantz/droidbox) - Herramienta dinámica de análisis de malware para Android, extensión a DECAF.
  * [drozer](https://github.com/FSecureLABS/drozer): herramienta de evaluación dinámica de vulnerabilidades de la plataforma Android.
  * [idb](https://www.idbtool.com/) - Analizador de seguridad de aplicaciones iOS.
  * [Inspeckage](https://github.com/ac-pm/Inspeckage) - Herramienta dinámica de análisis de paquetes de Android.
  
#### Editores hexadecimales
  * [Cheat Engine](https://www.cheatengine.org/) - Depurador de memoria y editor hexadecimal para ejecutar aplicaciones.
  * [Frhed](http://frhed.sourceforge.net/en/) - Editor de archivos binarios para Windows.
  * [HexEdit.js](https://hexed.it/) - Edición hexadecimal basada en navegador.
  * [Hexinator](https://hexinator.com/) - El mejor editor hexadecimal (propietario, comercial) del mundo.
  
#### Herramientas de análisis de formato de archivo
  * [Hachoir](https://hachoir.readthedocs.io/en/latest/index.html): biblioteca de Python para ver y editar un flujo binario como árbol de campos y herramientas para la extracción de metadatos.
  * [Estructura Kaitai](https://kaitai.io/) - Formatos de archivo y protocolos de red disección de lenguaje e IDE web, generando analizadores en C++, C#, Java, JavaScript, Perl, PHP, Python, Ruby.
  * [Veles](https://codisec.com/veles/) - Herramienta de visualización y análisis de datos binarios.

#### Herramientas de evasión antivirus
  * [AntiVirus Evasion Tool (AVET)](https://github.com/govolution/avet): exploits posteriores al proceso que contienen archivos ejecutables dirigidos a máquinas con Windows para evitar que el software antivirus los reconozca.
  * [Hyperion](https://nullsecurity.net/tools/binary.html) - Encriptador en tiempo de ejecución para ejecutables portátiles de 32 bits ("PE `.exe`s").
  * [peCloak.py](https://www.securitysift.com/pecloak-py-an-experiment-in-av-evasion/): automatiza el proceso de ocultar un ejecutable malicioso de Windows de la detección antivirus (AV).
  * [peCloakCapstone](https://github.com/v-p-b/peCloakCapstone): bifurcación multiplataforma de la herramienta automatizada de evasión antivirus de malware peCloak.py.
  * [Shellter](https://www.shellterproject.com/) - Herramienta de inyección de shellcode dinámico y el primer infector de PE verdaderamente dinámico jamás creado.
  * [SigThief](https://github.com/secretsquirrel/SigThief) - Robo de firmas para evadir AV.
  * [UniByAv](https://github.com/Mr-Un1k0d3r/UniByAv): ofuscador simple que toma código de shell sin formato y genera ejecutables aptos para antivirus mediante el uso de una clave XOR de 32 bits de fuerza bruta.
  * [Windows-SignedBinary](https://github.com/vysecurity/Windows-SignedBinary): herramienta de evasión AV para archivos binarios.

#### Herramientas de craqueo de hash
  * [CeWL](https://digi.ninja/projects/cewl.php): genera listas de palabras personalizadas rastreando el sitio web de un objetivo y recopilando palabras únicas.
  * [CrackStation](https://crackstation.net/) - Crackeador de contraseñas en línea.
  * [Hashcat](http://hashcat.net/hashcat/) - Utilidad de descifrado rápido de hash compatible con la mayoría de los hashes conocidos, así como con la aceleración de OpenCL y CUDA.
  * [Edición John the Ripper Jumbo] (https://github.com/openwall/john): versión mejorada de la comunidad de John the Ripper.
  * [John the Ripper](https://www.openwall.com/john/) - Rápido descifrador de contraseñas.
  * [JWT Cracker](https://github.com/lmammino/jwt-cracker) - Simple cracker de fuerza bruta de token HS256 JWT.
  * [Mentalista] (https://github.com/sc0tfree/mentalist): generador único de listas de palabras con contraseña basado en GUI compatible con CeWL y John the Ripper.
  * [Herramienta de recuperación de JPassword] (https://sourceforge.net/projects/jpassrecovery/) - Cracker de fuerza bruta RAR. Anteriormente llamado RAR Crack.

#### Utilidades de Windows
  * [Bloodhound](https://github.com/BloodHoundAD/BloodHound/wiki) - Explorador gráfico de relaciones de confianza de Active Directory.
  * [Comentador](https://github.com/clr2of8/Commentator): secuencia de comandos de PowerShell para agregar comentarios a documentos de MS Office, y estos comentarios pueden contener código para ejecutar.
  * [DeathStar](https://github.com/byt3bl33d3r/DeathStar): secuencia de comandos de Python que utiliza la API RESTful de Empire para automatizar la obtención de derechos de administrador de dominio en entornos de Active Directory.
  * [Empire](https://www.powershellempire.com/) - Agente de posexplotación de PowerShell puro.
  * [Fibratus](https://github.com/rabbitstack/fibratus) - Herramienta para exploración y seguimiento del kernel de Windows.
  * [GetVulnerableGPO](https://github.com/gpoguy/GetVulnerableGPO/): utilidad basada en PowerShell para encontrar GPO vulnerables.
  * [Headstart](https://github.com/GoVanguard/script-win-privescalate-headstart): la herramienta de escalada de privilegios de Windows de Lazy Man que utiliza PowerSploit.
  * [Hyena](https://www.systemtools.com/hyena/download.htm) - Explotación de NetBIOS.
  * [Luckystrike](https://github.com/curi0usJack/luckystrike): utilidad basada en PowerShell para la creación de documentos macro de Office maliciosos.
  * [Magic Unicorn](https://github.com/trustedsec/unicorn): generador de Shellcode para numerosos vectores de ataque, incluidas macros de Microsoft Office, PowerShell, aplicaciones HTML (HTA) o `certutil` (usando certificados falsos).
  * [Mimikatz](https://blog.gentilkiwi.com/mimikatz) - Herramienta de extracción de credenciales para el sistema operativo Windows.
  * [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - Marco de post-explotación de PowerShell.
  * [PSKernel-Primitives](https://github.com/FuzzySecurity/PSKernel-Primitives/) - Explotación de primitivas para PowerShell.
  * [Redsnarf](https://github.com/nccgroup/redsnarf): herramienta posterior a la explotación para recuperar hash de contraseñas y credenciales de estaciones de trabajo, servidores y controladores de dominio de Windows.
  * [Rubeus](https://github.com/GhostPack/Rubeus): Rubeus es un conjunto de herramientas de C# para la interacción y los abusos de Kerberos sin procesar.
  * [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite): las utilidades de solución de problemas de Sysinternals.
  * [Editor de credenciales de Windows](https://www.ampliasecurity.com/research/windows-credentials-editor/) - Inspeccione las sesiones de inicio de sesión y agregue, cambie, enumere y elimine las credenciales asociadas, incluidos los tickets de Kerberos.
  * [Sugerencia de exploits de Windows](https://github.com/AonCyberLabs/Windows-Exploit-Suggester): sugiere exploits de Windows según los niveles de parches.

#### Utilidades GNU Linux
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.
  * [Linux Exploit Suggester](https://github.com/InteliSecureLabs/Linux_Exploit_Suggester): informes heurísticos sobre exploits potencialmente viables para un sistema GNU/Linux determinado.
  * [Mempodipper](https://www.exploit-db.com/exploits/18411/) - Linux Kernel 2.6.39 < 3.2.2 script de escalada de privilegios locales.
  * [vuls](https://github.com/future-architect/vuls) - Escáner de vulnerabilidades sin agente Linux/FreeBSD.

#### Utilidades macOS
  * [Bella](https://github.com/khaleds-brain/Bella): Bella es una herramienta de minería de datos posterior a la explotación y una herramienta de administración remota de Python puro para macOS.
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.

#### Herramientas de ingeniería social
  * [Beelogger](https://github.com/4w4k3/BeeLogger) - Herramienta para generar keylooger.
  * [Catphish](https://github.com/ring0lab/catphish) - Herramienta para phishing y espionaje corporativo escrita en Ruby.
  * [Evilginx] (https://github.com/kgretzky/evilginx2): marco de ataque MITM utilizado para credenciales de phishing y cookies de sesión de cualquier servicio web
  * [Gophish](https://getgophish.com/) - Marco de phishing de código abierto
  * [King Phisher](https://github.com/rsmusllp/king-phisher): kit de herramientas de campaña de phishing utilizado para crear y administrar múltiples ataques de phishing simultáneos con correo electrónico personalizado y contenido del servidor.
  * [Lucy Phishing Server](https://lucysecurity.com/) - Herramienta (comercial) para realizar capacitaciones de concientización sobre seguridad para empleados, incluidas campañas de phishing personalizadas, ataques de malware, etc. Incluye muchas plantillas de ataque útiles, así como materiales de capacitación para aumentar la seguridad conciencia.
  * [PhishingFrenzshcat.net/hashcat/) - Utilidad de descifrado rápido de hash compatible con la mayoría de los hashes conocidos, así como con la aceleración de OpenCL y CUDA.
  * [Edición John the Ripper Jumbo] (https://github.com/openwall/john): versión mejorada de la comunidad de John the Ripper.
  * [John the Ripper](https://www.openwall.com/john/) - Rápido descifrador de contraseñas.
  * [JWT Cracker](https://github.com/lmammino/jwt-cracker) - Simple cracker de fuerza bruta de token HS256 JWT.
  * [Mentalista] (https://github.com/sc0tfree/mentalist): generador único de listas de palabras con contraseña basado en GUI compatible con CeWL y John the Ripper.
  * [Herramienta de recuperación de JPassword] (https://sourceforge.net/projects/jpassrecovery/) - Cracker de fuerza bruta RAR. Anteriormente llamado RAR Crack.

#### Utilidades de Windows
  * [Bloodhound](https://github.com/BloodHoundAD/BloodHound/wiki) - Explorador gráfico de relaciones de confianza de Active Directory.
  * [Comentador](https://github.com/clr2of8/Commentator): secuencia de comandos de PowerShell para agregar comentarios a documentos de MS Office, y estos comentarios pueden contener código para ejecutar.
  * [DeathStar](https://github.com/byt3bl33d3r/DeathStar): secuencia de comandos de Python que utiliza la API RESTful de Empire para automatizar la obtención de derechos de administrador de dominio en entornos de Active Directory.
  * [Empire](https://www.powershellempire.com/) - Agente de posexplotación de PowerShell puro.
  * [Fibratus](https://github.com/rabbitstack/fibratus) - Herramienta para exploración y seguimiento del kernel de Windows.
  * [GetVulnerableGPO](https://github.com/gpoguy/GetVulnerableGPO/): utilidad basada en PowerShell para encontrar GPO vulnerables.
  * [Headstart](https://github.com/GoVanguard/script-win-privescalate-headstart): la herramienta de escalada de privilegios de Windows de Lazy Man que utiliza PowerSploit.
  * [Hyena](https://www.systemtools.com/hyena/download.htm) - Explotación de NetBIOS.
  * [Luckystrike](https://github.com/curi0usJack/luckystrike): utilidad basada en PowerShell para la creación de documentos macro de Office maliciosos.
  * [Magic Unicorn](https://github.com/trustedsec/unicorn): generador de Shellcode para numerosos vectores de ataque, incluidas macros de Microsoft Office, PowerShell, aplicaciones HTML (HTA) o `certutil` (usando certificados falsos).
  * [Mimikatz](https://blog.gentilkiwi.com/mimikatz) - Herramienta de extracción de credenciales para el sistema operativo Windows.
  * [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - Marco de post-explotación de PowerShell.
  * [PSKernel-Primitives](https://github.com/FuzzySecurity/PSKernel-Primitives/) - Explotación de primitivas para PowerShell.
  * [Redsnarf](https://github.com/nccgroup/redsnarf): herramienta posterior a la explotación para recuperar hash de contraseñas y credenciales de estaciones de trabajo, servidores y controladores de dominio de Windows.
  * [Rubeus](https://github.com/GhostPack/Rubeus): Rubeus es un conjunto de herramientas de C# para la interacción y los abusos de Kerberos sin procesar.
  * [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite): las utilidades de solución de problemas de Sysinternals.
  * [Editor de credenciales de Windows](https://www.ampliasecurity.com/research/windows-credentials-editor/) - Inspeccione las sesiones de inicio de sesión y agregue, cambie, enumere y elimine las credenciales asociadas, incluidos los tickets de Kerberos.
  * [Sugerencia de exploits de Windows](https://github.com/AonCyberLabs/Windows-Exploit-Suggester): sugiere exploits de Windows según los niveles de parches.

#### Utilidades GNU Linux
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.
  * [Linux Exploit Suggester](https://github.com/InteliSecureLabs/Linux_Exploit_Suggester): informes heurísticos sobre exploits potencialmente viables para un sistema GNU/Linux determinado.
  * [Mempodipper](https://www.exploit-db.com/exploits/18411/) - Linux Kernel 2.6.39 < 3.2.2 script de escalada de privilegios locales.
  * [vuls](https://github.com/future-architect/vuls) - Escáner de vulnerabilidades sin agente Linux/FreeBSD.

#### Utilidades macOS
  * [Bella](https://github.com/khaleds-brain/Bella): Bella es una herramienta de minería de datos posterior a la explotación y una herramienta de administración remota de Python puro para macOS.
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.

#### Herramientas de ingeniería social
  * [Beelogger](https://github.com/4w4k3/BeeLogger) - Herramienta para generar keylooger.
  * [Catphish](https://github.com/ring0lab/catphish) - Herramienta para phishing y espionaje corporativo escrita en Ruby.
  * [Evilginx] (https://github.com/kgretzky/evilginx2): marco de ataque MITM utilizado para credenciales de phishing y cookies de sesión de cualquier servicio web
  * [Gophish](https://getgophish.com/) - Marco de phishing de código abierto
  * [King Phisher](https://github.com/rsmusllp/king-phisher): kit de herramientas de campaña de phishing utilizado para crear y administrar múltiples ataques de phishing simultáneos con correo electrónico personalizado y contenido del servidor.
  * [Lucy Phishing Server](https://lucysecurity.com/) - Herramienta (comercial) para realizar capacitaciones de concientización sobre seguridad para empleados, incluidas campañas de phishing personalizadas, ataques de malware, etc. Incluye muchas plantillas de ataque útiles, así como materiales de capacitación para aumentar la seguridad conciencia.
  * [PhishingFrenzshcat.net/hashcat/) - Utilidad de descifrado rápido de hash compatible con la mayoría de los hashes conocidos, así como con la aceleración de OpenCL y CUDA.
  * [Edición John the Ripper Jumbo] (https://github.com/openwall/john): versión mejorada de la comunidad de John the Ripper.
  * [John the Ripper](https://www.openwall.com/john/) - Rápido descifrador de contraseñas.
  * [JWT Cracker](https://github.com/lmammino/jwt-cracker) - Simple cracker de fuerza bruta de token HS256 JWT.
  * [Mentalista] (https://github.com/sc0tfree/mentalist): generador único de listas de palabras con contraseña basado en GUI compatible con CeWL y John the Ripper.
  * [Herramienta de recuperación de JPassword] (https://sourceforge.net/projects/jpassrecovery/) - Cracker de fuerza bruta RAR. Anteriormente llamado RAR Crack.

#### Utilidades de Windows
  * [Bloodhound](https://github.com/BloodHoundAD/BloodHound/wiki) - Explorador gráfico de relaciones de confianza de Active Directory.
  * [Comentador](https://github.com/clr2of8/Commentator): secuencia de comandos de PowerShell para agregar comentarios a documentos de MS Office, y estos comentarios pueden contener código para ejecutar.
  * [DeathStar](https://github.com/byt3bl33d3r/DeathStar): secuencia de comandos de Python que utiliza la API RESTful de Empire para automatizar la obtención de derechos de administrador de dominio en entornos de Active Directory.
  * [Empire](https://www.powershellempire.com/) - Agente de posexplotación de PowerShell puro.
  * [Fibratus](https://github.com/rabbitstack/fibratus) - Herramienta para exploración y seguimiento del kernel de Windows.
  * [GetVulnerableGPO](https://github.com/gpoguy/GetVulnerableGPO/): utilidad basada en PowerShell para encontrar GPO vulnerables.
  * [Headstart](https://github.com/GoVanguard/script-win-privescalate-headstart): la herramienta de escalada de privilegios de Windows de Lazy Man que utiliza PowerSploit.
  * [Hyena](https://www.systemtools.com/hyena/download.htm) - Explotación de NetBIOS.
  * [Luckystrike](https://github.com/curi0usJack/luckystrike): utilidad basada en PowerShell para la creación de documentos macro de Office maliciosos.
  * [Magic Unicorn](https://github.com/trustedsec/unicorn): generador de Shellcode para numerosos vectores de ataque, incluidas macros de Microsoft Office, PowerShell, aplicaciones HTML (HTA) o `certutil` (usando certificados falsos).
  * [Mimikatz](https://blog.gentilkiwi.com/mimikatz) - Herramienta de extracción de credenciales para el sistema operativo Windows.
  * [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) - Marco de post-explotación de PowerShell.
  * [PSKernel-Primitives](https://github.com/FuzzySecurity/PSKernel-Primitives/) - Explotación de primitivas para PowerShell.
  * [Redsnarf](https://github.com/nccgroup/redsnarf): herramienta posterior a la explotación para recuperar hash de contraseñas y credenciales de estaciones de trabajo, servidores y controladores de dominio de Windows.
  * [Rubeus](https://github.com/GhostPack/Rubeus): Rubeus es un conjunto de herramientas de C# para la interacción y los abusos de Kerberos sin procesar.
  * [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite): las utilidades de solución de problemas de Sysinternals.
  * [Editor de credenciales de Windows](https://www.ampliasecurity.com/research/windows-credentials-editor/) - Inspeccione las sesiones de inicio de sesión y agregue, cambie, enumere y elimine las credenciales asociadas, incluidos los tickets de Kerberos.
  * [Sugerencia de exploits de Windows](https://github.com/AonCyberLabs/Windows-Exploit-Suggester): sugiere exploits de Windows según los niveles de parches.

#### Utilidades GNU Linux
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.
  * [Linux Exploit Suggester](https://github.com/InteliSecureLabs/Linux_Exploit_Suggester): informes heurísticos sobre exploits potencialmente viables para un sistema GNU/Linux determinado.
  * [Mempodipper](https://www.exploit-db.com/exploits/18411/) - Linux Kernel 2.6.39 < 3.2.2 script de escalada de privilegios locales.
  * [vuls](https://github.com/future-architect/vuls) - Escáner de vulnerabilidades sin agente Linux/FreeBSD.

#### Utilidades macOS
  * [Bella](https://github.com/khaleds-brain/Bella): Bella es una herramienta de minería de datos posterior a la explotación y una herramienta de administración remota de Python puro para macOS.
  * [Linus](https://cisofy.com/lynis/) - Herramienta de auditoría de seguridad para Linux y macOS.

#### Herramientas de ingeniería social
  * [Beelogger](https://github.com/4w4k3/BeeLogger) - Herramienta para generar keylooger.
  * [Catphish](https://github.com/ring0lab/catphish) - Herramienta para phishing y espionaje corporativo escrita en Ruby.
  * [Evilginx] (https://github.com/kgretzky/evilginx2): marco de ataque MITM utilizado para credenciales de phishing y cookies de sesión de cualquier servicio web
  * [Gophish](https://getgophish.com/) - Marco de phishing de código abierto
  * [King Phisher](https://github.com/rsmusllp/king-phisher): kit de herramientas de campaña de phishing utilizado para crear y administrar múltiples ataques de phishing simultáneos con correo electrónico personalizado y contenido del servidor.
  * [Lucy Phishing Server](https://lucysecurity.com/) - Herramienta (comercial) para realizar capacitaciones de concientización sobre seguridad para empleados, incluidas campañas de phishing personalizadas, ataques de malware, etc. Incluye muchas plantillas de ataque útiles, así como materiales de capacitación para aumentar la seguridad conciencia.
  * [PhishingFrenz
