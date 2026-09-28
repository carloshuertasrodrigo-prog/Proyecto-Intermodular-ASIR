# 4. Establecer requisitos

En este apartado se definen los requisitos que debe cumplir la infraestructura informática de VeraVel. Se establecen los requisitos funcionales, no funcionales y de negocio, además de los requisitos relacionados con los diferentes módulos de ASIR.

También se incluye una matriz de trazabilidad para relacionar los requisitos con las partes del proyecto que permiten cumplirlos.

## 4.1. Requisitos funcionales

Los requisitos funcionales describen las funciones y servicios que debe proporcionar la infraestructura informática de VeraVel.

| **Código** | **Requisito funcional** |
|---|---|
| RF-01 | El sistema deberá permitir la gestión de los usuarios y sus permisos de acceso. |
| RF-02 | El sistema deberá proporcionar un servicio DHCP para asignar direcciones IP a los equipos de la red. |
| RF-03 | El sistema deberá proporcionar un servicio DNS para resolver los nombres de los equipos y servicios de la infraestructura. |
| RF-04 | El sistema deberá proporcionar un servicio web para alojar la página corporativa de VeraVel. |
| RF-05 | El sistema deberá proporcionar un servicio FTP para permitir la transferencia de archivos. |
| RF-06 | La base de datos deberá permitir almacenar y gestionar información de clientes, envíos, paquetes y otros elementos relacionados con la actividad de la empresa. |
| RF-07 | La página web deberá permitir mostrar información corporativa de VeraVel. |
| RF-08 | El sistema deberá permitir realizar pruebas de conectividad entre los diferentes equipos y servicios de la infraestructura. |
| RF-09 | El sistema deberá permitir realizar copias de seguridad de la información importante. |
| RF-10 | El sistema deberá permitir administrar los servicios y recursos de la infraestructura desde el entorno de servidor. |

## 4.2. Requisitos no funcionales

Los requisitos no funcionales establecen las características que debe cumplir la infraestructura informática para garantizar un funcionamiento adecuado.

| **Código** | **Requisito no funcional** |
|---|---|
| RNF-01 | La infraestructura deberá disponer de mecanismos básicos de seguridad para proteger los sistemas y la información. |
| RNF-02 | Los usuarios deberán disponer únicamente de los permisos necesarios para realizar sus funciones. |
| RNF-03 | Los servicios deberán estar configurados de forma que permitan una administración organizada de la infraestructura. |
| RNF-04 | La infraestructura deberá permitir realizar copias de seguridad de la información importante. |
| RNF-05 | Los servicios deberán ofrecer un funcionamiento estable durante su utilización. |
| RNF-06 | La infraestructura deberá poder ampliarse en el futuro según las necesidades de VeraVel. |
| RNF-07 | La documentación técnica deberá permitir comprender y mantener la configuración realizada. |
| RNF-08 | Los servicios deberán poder comprobarse mediante pruebas de conectividad y funcionamiento. |

## 4.3. Requisitos de negocio

Los requisitos de negocio definen las necesidades principales de VeraVel que justifican el desarrollo de la infraestructura informática.

| **Código** | **Requisito de negocio** |
|---|---|
| RN-01 | La empresa deberá disponer de una infraestructura informática centralizada para organizar sus recursos y servicios. |
| RN-02 | La infraestructura deberá facilitar la gestión de la información relacionada con clientes, envíos y paquetes. |
| RN-03 | La empresa deberá disponer de una página web corporativa para mejorar su presencia digital. |
| RN-04 | La infraestructura deberá facilitar la administración y mantenimiento de los servicios informáticos. |
| RN-05 | El sistema deberá permitir ampliar la infraestructura en función del crecimiento y las necesidades futuras de la empresa. |
| RN-06 | La información de la empresa deberá gestionarse de forma organizada y con medidas básicas de protección. |

## 4.4. Requisitos por módulos de ASIR

### 4.4.1. ASGBD - Administración de Sistemas Gestores de Bases de Datos

El proyecto deberá disponer de una base de datos que permita almacenar y gestionar de forma organizada la información relacionada con la actividad de VeraVel.

| **Código** | **Requisito** |
|---|---|
| ASGBD-01 | La base de datos deberá permitir almacenar información de clientes. |
| ASGBD-02 | La base de datos deberá permitir gestionar la información de los envíos y paquetes. |
| ASGBD-03 | La información deberá estar organizada mediante tablas y relaciones. |
| ASGBD-04 | El sistema gestor de bases de datos deberá permitir realizar consultas y gestionar la información almacenada. |
| ASGBD-05 | Se deberán realizar copias de seguridad de la información de la base de datos. |

### 4.4.2. ASO - Administración de Sistemas Operativos

El proyecto deberá utilizar un sistema operativo de servidor que permita instalar, configurar y administrar los servicios necesarios para la infraestructura.

| **Código** | **Requisito** |
|---|---|
| ASO-01 | El servidor deberá utilizar un sistema operativo Linux. |
| ASO-02 | El sistema deberá permitir administrar usuarios y grupos. |
| ASO-03 | El sistema deberá permitir configurar permisos de acceso a los recursos. |
| ASO-04 | El sistema deberá permitir instalar y administrar los servicios necesarios para el proyecto. |
| ASO-05 | El sistema deberá permitir realizar tareas de administración y mantenimiento del servidor. |

### 4.4.3. IAW - Implantación de Aplicaciones Web

El proyecto deberá disponer de una página web corporativa que permita presentar información de VeraVel y que pueda ser alojada en el servidor web de la infraestructura.

| **Código** | **Requisito** |
|---|---|
| IAW-01 | La infraestructura deberá disponer de un servidor web para alojar la página corporativa. |
| IAW-02 | La página web deberá estar desarrollada utilizando HTML y CSS. |
| IAW-03 | La página web deberá mostrar información relacionada con VeraVel. |
| IAW-04 | La página web deberá poder ser accesible desde los equipos autorizados de la red. |
| IAW-05 | El servicio web deberá poder comprobarse mediante pruebas de acceso y funcionamiento. |

### 4.4.4. Servicios de Red e Internet

El proyecto deberá disponer de los servicios de red necesarios para permitir la comunicación y el funcionamiento de los diferentes equipos y servicios de la infraestructura.

| **Código** | **Requisito** |
|---|---|
| SRI-01 | La infraestructura deberá disponer de un servicio DHCP para la asignación automática de direcciones IP. |
| SRI-02 | La infraestructura deberá disponer de un servicio DNS para la resolución de nombres. |
| SRI-03 | La infraestructura deberá disponer de un servicio HTTP para alojar la página web. |
| SRI-04 | La infraestructura deberá disponer de un servicio FTP para la transferencia de archivos. |
| SRI-05 | Los diferentes equipos y servicios deberán poder comunicarse correctamente dentro de la red. |
| SRI-06 | Se deberán realizar pruebas de conectividad para comprobar el funcionamiento de la infraestructura. |

