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
   - Elección de licencia para el repositorio de _GitHub_. Diferencias básicas entre _copyright_, _Creative Commons_ y licencias de software libre.
     
[2. Estructuras estáticas y programación modular]() `1ºT`

[:open_file_folder: *PROYECTO: problema libre OICV/OIE*]()

[3. Sistemas informáticos y redes]() `2ºT`
  - Características generales de los dispositivos digitales. Componentes básicos de un sistema informático.
  - Monitorización de componentes hardware con _HWinfo_. Uso de _Prime95_ para estresar la _CPU_.
  - Prueba de rendimiento del disco duro con _CrystalDiskMark_.
  - Sistemas Operativos. Instalación de Máquinas Virtuales y comandos de consola básicos.
  - Dispositivos de red y canales de interconexión. Parámetros típicos y comandos de red básicos.
  - Configuración de red simulada con _Cisco Packet Tracer_/_GNS3_.
    
[4. Introducción al desarrollo web]() `2ºT`
  - _HTML + CSS_. Alojamiento web en _GitHub_.
  - _WordPress (XAMPP)_.
  - Desarrollo web con IA. Herramienta _Teachable Machine_ para reconocimiento de imágenes.
    
[:open_file_folder: *PROYECTO: Expertos en componentes*]()
  - Crear sitio web con info de la exposición. Deben integrar funcionalidad TM para reconocer tipos del componente escogido.
  - Consumo, durabilidad, reparabilidad e impacto ambiental del componente.
    
[5. Seguridad informática]() `3ºT`
  - Tipos de seguridad. Amenazas y ataques.
    - `virus.bat`.
    - Hackear sitios web creados en _Wordpress_.
    - `IP Logger`: robar dirección IP pública tras hacer _click_ en un enlace.
    - `';--have i been pwned?`: cómo saber si tus contraseñas se han filtrado en Internet.
  - Copias de seguridad y almacenamiento. 
    - Creación y administración de copias de seguridad en Linux con rsync.
    - Discos virtuales y configuración _RAID_.
  - Gestión de imágenes del sistema.
    - _Clonezilla_ (crear y restaurar ISO). 
  - Criptografía: VPN, firmas y certificados digitales, criptomonedas y estrategias para la detección de fraudes online (HTTPS/SSL TLS vs HTTP).
    - `Asimétrica` Uso de _GPG_ para firmar y verificar mensajes.
    - `Simétrica` Cifrado de datos con _VeraCrypt_.
    - `Funciones hash` Crackeo de contraseñas con _Hashcat_.
  - Seguridad en redes inalámbricas (_Wi-Fi_).

---

Diseñar la infraestructura informática de una pequeña organización, justificando los equipos, el sistema operativo, el direccionamiento, la topología, las medidas básicas de seguridad y el presupuesto.

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




