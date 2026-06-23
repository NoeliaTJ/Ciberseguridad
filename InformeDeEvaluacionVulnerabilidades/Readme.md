Este documento es un simuclacro inventado de un curso que hice de varios meses de Ciberseguridad.
Este en concreto está hecho de principios de enero. Simplemente se va a revisar la seguridad de una base de datos importante para marketing, mirando quién puede entrar, qué permisos tiene, si los datos están bien protegidos y qué ataques podrían pasar. Luego se proponen medidas para reducir el riesgo. Insisto en la parte en que estoy aprendiendo y este github es un lugar donde dejo con cariño lo que me apetece plasmar lo que aprendo en ciertos momentos.

He aquí una parte explicatoria de los conceptos básicos de lo que se incluye en este documento, separados por secciones, ya que se tratan partes de seguridad y datos.
SSL/TLS: son sistemas que cifran la comunicación entre dos equipos para que nadie pueda leer lo que se envía por la red. Hoy en día, lo correcto es hablar más de TLS, que es la versión moderna y segura.

Cifrado: convertir datos en un formato ilegible para cualquiera que no tenga la clave.

Cifrado en tránsito: protege los datos mientras viajan por la red.

Cifrado en reposo: protege los datos cuando están guardados en disco.

IPv4: es el sistema de direcciones de red, como la “dirección postal” de un dispositivo en internet o en una red interna.

VLAN: es una forma de separar redes dentro de la misma infraestructura para que unas máquinas no se mezclen con otras.

IP allow-listing: solo dejas entrar conexiones desde direcciones IP concretas que tú autorizas.

Base de datos y MySQL
MySQL: es un sistema para guardar y gestionar datos en tablas.

Servidor de base de datos: el ordenador o máquina donde vive esa base de datos.

DDL: significa Data Definition Language. Son las órdenes que sirven para crear o cambiar estructuras de la base de datos, como tablas.

Ejemplos: CREATE, ALTER, DROP.

DML: significa Data Manipulation Language. Son las órdenes para trabajar con los datos dentro de las tablas.

Ejemplos: SELECT, INSERT, UPDATE, DELETE.

SQL injection: un ataque en el que alguien intenta meter código SQL malicioso para leer, modificar o borrar datos.

Consultas SQL: preguntas o instrucciones que se le hacen a la base de datos.

Privilegios: permisos que tiene un usuario para hacer cosas en la base de datos.

Permisos excesivos: cuando alguien tiene más permisos de los que necesita.

Cuentas de terceros: usuarios o accesos de proveedores externos.

Control de acceso
AAA: siglas de Autenticación, Autorización y Auditoría.

Autenticación: demostrar quién eres, por ejemplo con usuario y contraseña.

Autorización: decidir qué puedes hacer.

Auditoría: registrar lo que haces para poder revisarlo después.

RBAC: Role-Based Access Control. Acceso basado en roles.

Ejemplo: “administrador”, “analista”, “lector”.

Menor privilegio: cada usuario solo debe tener los permisos mínimos necesarios.

MFA: autenticación multifactor. No basta con contraseña; hace falta otro paso, como un código móvil o app.

Riesgos y ataques
Exfiltración de datos: robo de datos sacándolos de la empresa.

Ransomware: malware que bloquea o cifra archivos y pide rescate.

Malware: programa malicioso.

Ingeniería social: engañar a una persona para que entregue datos o acceso.

Acceso no autorizado: entrar sin permiso.

Credenciales comprometidas: usuario y contraseña que han sido robados o descubiertos.

Auditoría y monitorización
Auditoría: registro de quién hizo qué y cuándo.

Logs: archivos donde se guardan eventos y acciones del sistema.

Monitorización: vigilancia continua para detectar problemas.

DAM: Database Activity Monitoring. Herramienta que vigila la actividad de la base de datos.

Comportamiento anómalo: actividad rara o fuera de lo normal.

Copias y continuidad
Backups: copias de seguridad.

Offline: guardado desconectado de la red, para que un ataque no lo borre también.

Recuperación: volver a poner en marcha los datos si algo falla.

Otros términos
RGPD: ley europea de protección de datos personales.

Confidencialidad: que solo vea los datos quien debe verlos.

Integridad: que los datos no se alteren sin permiso.

Disponibilidad: que el sistema esté accesible cuando se necesita.

Activos críticos: cosas muy importantes para el negocio, como la base de datos de clientes.

Análisis de vulnerabilidades: revisar el sistema para encontrar fallos de seguridad.

Riesgo residual: el riesgo que queda incluso después de aplicar medidas de seguridad.
