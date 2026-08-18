# Tarea Práctica 3: Diseño de OUs en Active Directory

## Descripción

Esta práctica tiene como objetivo diseñar e implementar una estructura organizativa en **Active Directory** utilizando **Windows Server**.

Durante el desarrollo de la práctica se realizó la creación y organización de **Unidades Organizativas (OUs), grupos, usuarios y equipos**, siguiendo una estructura definida para facilitar la administración de los recursos del dominio.

También se realizó la configuración y comprobación de permisos mediante grupos de seguridad, verificando el acceso de los usuarios a los recursos compartidos según su pertenencia a los grupos correspondientes.

## Objetivos

* Diseñar una estructura de Unidades Organizativas (OUs).
* Crear y organizar usuarios dentro de Active Directory.
* Crear grupos de seguridad para administrar permisos.
* Incorporar equipos a la estructura organizativa.
* Asignar usuarios a los grupos correspondientes.
* Configurar permisos sobre recursos compartidos.
* Comprobar la aplicación de permisos mediante grupos.

## Tecnologías utilizadas

* Windows Server 2025
* Active Directory Domain Services (AD DS)
* Oracle VirtualBox
* Active Directory Users and Computers
* Grupos de seguridad
* Recursos compartidos de Windows

## Estructura del proyecto

```text
Tarea-Practica-3-Diseno-OU/
│
├── Documento/
│   └── Tarea-Practica-3-Diseno-OU.pdf
│
├── Evidencias/
│   ├── 01-Server-Manager.png
│   ├── 02-Dominio.png
│   ├── 03-OUs.png
│   ├── 04-Grupos.png
│   ├── 05-Usuarios.png
│   ├── 06-Equipos.png
│   ├── 07-Permisos.png
│   └── 08-Prueba-Permisos.png
│
└── README.md
```

## Actividades realizadas

### 1. Diseño de OUs

Se diseñó una estructura de Unidades Organizativas para organizar los diferentes objetos del dominio de Active Directory.

### 2. Creación de grupos

Se crearon grupos de seguridad para facilitar la administración de usuarios y la asignación de permisos de acuerdo con las áreas o funciones establecidas.

### 3. Creación de usuarios

Se crearon los usuarios correspondientes y se organizaron dentro de las OUs definidas.

### 4. Organización de equipos

Se incorporaron y organizaron los equipos dentro de la estructura de Active Directory.

### 5. Asignación de usuarios a grupos

Los usuarios fueron agregados a los grupos correspondientes para permitir una administración centralizada de los permisos.

### 6. Configuración de permisos

Se configuraron permisos sobre un recurso compartido utilizando grupos de seguridad de Active Directory.

### 7. Prueba de aplicación de permisos

Se realizó una prueba con un usuario perteneciente al grupo autorizado y con un usuario que no pertenece a dicho grupo.

El usuario autorizado pudo acceder al recurso de acuerdo con los permisos asignados, mientras que el usuario no autorizado presentó un nivel de acceso diferente según la configuración realizada.

## Evidencias

Las capturas del proceso de configuración y las pruebas realizadas se encuentran en la carpeta **Evidencias**.

La documentación completa de la práctica se encuentra en la carpeta **Documento**.

## Autor

**Luciano Gómez**

Práctica académica de administración de sistemas y Active Directory.
