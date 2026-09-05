# :school_satchel: Programación, Redes y Sistemas Informáticos - 2º BACH _(curso 26-27)_

> Curso auxiliar para el alumnado de **PRSI II** :man_technologist:
>> *"Lo MEJOR de la programación es que hace lo que dices."*
>>> *"Lo PEOR de la programación es que hace lo que dices."*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="prsi.PNG" width="" height="">

## :books: Planificación y secuenciación

`Noticiario` Recopilación sobre hechos interesantes de IA o Seguridad que ocurran durante el curso para comentar en clase.

`Bienvenida` [Buenas prácticas y Autorregulación del uso del móvil]() 

`BONUS` [Uso responsable de la IA como estudiantes]() 
   - Sesgos y errores en LLMs.
   - Uso de _NotebookLM_.
   - Copilot: modo razonamiento profundo. Agente _Prompt coach_ de M365.
   - Creación de Agentes de IA personalizados como herramienta para el estudio.
   - Protocolo de uso de IA:
      - Cuándo se puede utilizar.
      - Cómo debe declararse su uso (propiedad intelectual y atribución de contenido generado o transformado con IA). Evidencias que debe conservar el alumnado.
      - Cómo se comprueba que el estudiante comprende lo entregado.
      - Qué datos no deben introducirse en una herramienta externa.
     
[1. Introducción a la Programación. Estructuras condicionales e iterativas]() `1ºT`
  
     
[2. Estructuras estáticas y programación modular]() `1ºT`

[:open_file_folder: *PROYECTO: problema libre OICV/OIE*]()
   - Elección de licencia para el repositorio de _GitHub_. Diferencias básicas entre _copyright_, _Creative Commons_ y licencias de software libre.
   - _Markdown_ para documentación.
   - Pruebas.

[3. Sistemas informáticos y redes]() `2ºT`
  - Características generales de los dispositivos digitales. Componentes básicos de un sistema informático.
  - Monitorización de componentes hardware con _HWinfo_. Uso de _Prime95_ para estresar la _CPU_.
  - Prueba de rendimiento del disco duro con _CrystalDiskMark_.
  - Sistemas Operativos. Instalación de Máquinas Virtuales y comandos de consola básicos.
  - Dispositivos de red y canales de interconexión. Parámetros típicos y comandos de red básicos.
  - Configuración de red simulada con _Cisco Packet Tracer_.
    
[4. Introducción al desarrollo web]() `2ºT`
  - _HTML + CSS_. Alojamiento web en _GitHub Pages_.
  - _WordPress (XAMPP)_.
  - Desarrollo web con IA. Herramienta _Teachable Machine_ para reconocimiento de imágenes.
    
[:open_file_folder: *PROYECTO: Expertos en componentes*]()
  - Crear sitio web con info de la exposición. Deben integrar funcionalidad TM para reconocer tipos del componente escogido.
  - Consumo, durabilidad, reparabilidad e impacto ambiental del componente.
    
[5. Seguridad informática]() `3ºT`
  - Tipos de seguridad. Amenazas y ataques.
    - `virus.bat`.
    - Hackear sitios web creados en _WordPress_.
    - `IP Logger`: robar dirección IP pública tras hacer _click_ en un enlace.
    - `';--have i been pwned?`: cómo saber si tus contraseñas se han filtrado en Internet.
  - Copias de seguridad y almacenamiento. 
    - Creación y administración de copias de seguridad en Linux con rsync.
    - Discos virtuales y configuración _RAID_.
  - Gestión de imágenes del sistema.
    - _Clonezilla_ (crear y restaurar ISO). 
  - Criptografía: VPN, firmas y certificados digitales, criptomonedas y estrategias para la detección de fraudes online (HTTP vs HTTPS/SSL TLS).
    - `Asimétrica` Uso de _GPG_ para firmar y verificar mensajes.
    - `Simétrica` Cifrado de datos con _VeraCrypt_.
    - `Funciones hash` Crackeo de contraseñas con _Hashcat_.
  - Seguridad en redes inalámbricas (_Wi-Fi_).

---

| Temas y Proyectos | CE1 Programación | CE2 Sistemas | CE3 Redes | CE4 Servicios en red | CE5 Ciudadanía digital |
|---|---:|---:|---:|---:|---:|
| Bienvenida, Noticiario y uso responsable de la IA | 5 % | 0 % | 0 % | 0 % | 25 % |
| 1. Introducción a la programación | 35 % | 0 % | 0 % | 0 % | 10 % |
| 2. Estructuras estáticas y programación modular | 45 % | 0 % | 0 % | 0 % | 10 % |
| Proyecto OICV/OIE | 10 % | 0 % | 0 % | 0 % | 10 % |
| 3. Sistemas informáticos y redes | 0 % | 55 % | 65 % | 0 % | 15 % |
| 4. Introducción al desarrollo web | 5 % | 0 % | 0 % | 55 % | 5 % |
| Proyecto «Expertos en componentes» | 0 % | 15 % | 0 % | 15 % | 10 % |
| 5. Seguridad informática | 0 % | 30 % | 35 % | 30 % | 15 % |
| **Total de cada competencia** | **100 %** | **100 %** | **100 %** | **100 %** | **100 %** |

--- 
NO MIRAR 

Proyecto 1º - Experto en componentes
Proyecto 2º NOTA FINAL DEL CURSO A PARTIR DE AQUÍ, BONUS... - Diseñar la infraestructura informática de una pequeña organización, justificando los equipos, el sistema operativo, el direccionamiento, la topología, las medidas básicas de seguridad y el presupuesto. Simulación de red creada.

*WordPress o desarrollo web:*
Explicar brevemente que WordPress utiliza una base de datos.
Entrar en phpMyAdmin.
Ver tablas, registros y relaciones básicas.
Hacer consultas SQL sencillas con SELECT, INSERT y UPDATE.
Conectar, si da tiempo, una aplicación mínima a una base de datos.

*Servicios compartidos en red*
Tienes redes y copias mediante rsync, pero dejaría expresamente alguna práctica de:
carpetas compartidas;
permisos de usuarios;
intercambio de archivos entre máquinas virtuales;
acceso desde varios sistemas operativos.
Podría encajar naturalmente en el bloque de máquinas virtuales: una máquina actúa como servidor y otras acceden a un recurso compartido.

| Bloque | 1.º de Bachillerato | 2.º de Bachillerato |
|---|---|---|
| Programación | Python: variables, condicionales, bucles y funciones | Python: estructuras de datos, programación modular, pruebas y depuración |
| Repositorios | GitHub y Markdown básico | Documentación, licencias y gestión de proyectos en GitHub |
| Hardware | HWiNFO, Prime95 y CrystalDiskMark | Selección y evaluación de equipos según rendimiento, coste y consumo |
| Sistemas operativos | Windows/Linux, comandos básicos y máquinas virtuales | Administración de Linux, usuarios, grupos, permisos y servicios |
| Virtualización | VirtualBox: instalación, configuración e instantáneas | Redes virtuales y modelos cliente-servidor |
| Redes | Cisco Packet Tracer: dispositivos, IP, topologías y comandos básicos | Packet Tracer/GNS3: diseño, configuración, diagnóstico y seguridad |
| Servicios en red | Introducción a recursos de red | Carpetas compartidas, permisos, Samba/NFS y acceso entre sistemas |
| Desarrollo web | HTML, CSS y GitHub Pages | Web avanzada e integración de servicios e IA |
| CMS | WordPress con XAMPP: instalación, temas, páginas, menús y usuarios | WordPress con phpMyAdmin: tablas, registros, mantenimiento y seguridad |
| Bases de datos | Introducción a la base de datos de WordPress | phpMyAdmin y SQL básico: SELECT, INSERT y UPDATE |
| Inteligencia artificial | NotebookLM, Copilot, Prompt Coach y uso responsable de LLM | Agentes personalizados, Teachable Machine e IA aplicada a proyectos |
| Copias de seguridad | Copias básicas e instantáneas de máquinas virtuales | rsync, RAID, Clonezilla y restauración de sistemas |
| Criptografía | Contraseñas, autenticación y privacidad | GPG, VeraCrypt, hashes, TLS, certificados y firmas digitales |
| Ciberseguridad | Amenazas, malware, filtraciones y seguridad básica | Auditoría de WordPress, Hashcat, seguridad Wi-Fi y análisis del rastreo web |




