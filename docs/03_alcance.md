# 3. Definir alcance

En este apartado se define el alcance del proyecto de infraestructura informática de VeraVel. Se establecen las funciones que formarán parte del proyecto, los aspectos que quedan fuera de él, las tecnologías que se utilizarán, la planificación temporal y los recursos necesarios.

## 3.1. Alcance funcional

El proyecto incluye el diseño e implementación de una infraestructura informática para VeraVel que permita centralizar y organizar los principales recursos y servicios informáticos de la empresa.

### Incluye

- Diseño de la infraestructura de red.
- Configuración de un servidor basado en Linux.
- Configuración de servicios de red como DHCP, DNS, HTTP y FTP.
- Diseño e implementación de una base de datos para gestionar la información de clientes, envíos, paquetes y otros elementos relacionados con la actividad de la empresa.
- Desarrollo de una página web corporativa.
- Integración de los diferentes servicios de la infraestructura.
- Configuración de máquinas virtuales para separar determinados servicios.
- Configuración de medidas básicas de seguridad, usuarios y permisos.
- Realización de pruebas de funcionamiento y conectividad.
- Elaboración de la documentación técnica del proyecto.

### No incluye

- La instalación física de toda la infraestructura en las instalaciones reales de VeraVel.
- La adquisición real de servidores, switches u otros equipos.
- La contratación de servicios externos de Internet.
- El desarrollo de una aplicación móvil.
- La implantación de sistemas informáticos que no estén relacionados con los objetivos definidos para este proyecto.

## 3.2. Alcance técnico

El proyecto contempla el diseño y configuración de una infraestructura informática basada en tecnologías de virtualización y servicios de red.

Las principales tecnologías y plataformas consideradas son:

- **Linux Server** como sistema operativo para los servicios de servidor.
- **VirtualBox** para la creación y gestión de máquinas virtuales.
- **GNS3** para el diseño y simulación de la infraestructura de red.
- **Docker** como tecnología que puede utilizarse para ejecutar determinados servicios de forma aislada.
- **MariaDB** como sistema gestor de bases de datos.
- **Apache** para el servicio web.
- **DHCP y DNS** para la configuración y resolución de la red.
- **FTP** para la transferencia de archivos.
- **HTML y CSS** para el desarrollo de la página web corporativa.

El alcance técnico se centra en diseñar, configurar y probar estos elementos dentro del entorno de trabajo del proyecto. La elección definitiva de la plataforma de virtualización se justificará en un apartado posterior.

## 3.3. Alcance temporal

El proyecto se desarrollará mediante diferentes fases, desde el análisis inicial hasta la realización de pruebas y la documentación final.

| **Fase** | **Actividad principal** | **Entregable** |
|---|---|---|
| 1 | Análisis de necesidades y diseño | Análisis y diseño inicial |
| 2 | Diseño y configuración de la red | Diseño de la infraestructura de red |
| 3 | Configuración de servicios | Servicios de red configurados |
| 4 | Diseño e implementación de la base de datos | Base de datos funcional |
| 5 | Desarrollo de la página web | Página web corporativa |
| 6 | Pruebas de funcionamiento | Resultados de las pruebas |
| 7 | Documentación | Documentación técnica final |

Estas fases permiten organizar el desarrollo del proyecto de forma progresiva, comprobando el funcionamiento de cada parte antes de continuar con la siguiente.

## 3.4. Alcance de recursos

Para desarrollar el proyecto serán necesarios recursos humanos, materiales y económicos.

### Recursos humanos

El proyecto requiere diferentes perfiles relacionados con la administración de sistemas, redes, bases de datos y desarrollo web:

- Administrador de sistemas.
- Técnico de redes.
- Técnico de bases de datos.
- Desarrollador web.

### Recursos materiales y software

Entre los principales recursos necesarios se encuentran:

- Servidor para alojar la infraestructura.
- Equipos de red, como routers y switches.
- Equipos cliente.
- Sistema de alimentación ininterrumpida (SAI).
- Rack y elementos de organización del cableado.
- Sistema de almacenamiento para las copias de seguridad.
- Sistema operativo Linux Server.
- VirtualBox.
- GNS3.
- MariaDB.
- Apache.
- Herramientas de desarrollo web.

### Presupuesto

El presupuesto debe contemplar tanto los equipos necesarios para la infraestructura como los recursos relacionados con su configuración y puesta en funcionamiento.

Como referencia para el proyecto, se tendrá en cuenta el coste del equipamiento, el software necesario y las horas de trabajo dedicadas al diseño, configuración, pruebas y documentación.

## 3.5. Elección y justificación de la plataforma de virtualización

Para el desarrollo del proyecto se utilizará GNS3 como plataforma principal para diseñar y simular la infraestructura de red.

GNS3 permite representar la topología de red y comprobar el funcionamiento de los diferentes dispositivos y conexiones antes de realizar una posible implantación física.

Se ha elegido GNS3 porque el proyecto necesita trabajar principalmente con una infraestructura de red formada por diferentes dispositivos y servicios. Además, permite realizar pruebas y detectar posibles problemas de configuración durante la fase de desarrollo.

Para la ejecución de los servidores y máquinas virtuales se utilizará VirtualBox, que permitirá crear los entornos virtualizados necesarios para instalar y configurar los sistemas operativos y servicios del proyecto.

Por tanto, GNS3 se utilizará principalmente para el diseño y simulación de la red, mientras que VirtualBox se utilizará para la virtualización de los servidores y equipos necesarios.

