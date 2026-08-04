# Sistema de Gestión de Inventario para Mini Súper

Sistema desarrollado para optimizar la administración de inventario, productos, proveedores y ventas del Mini Súper **Los Tres Hermanos**, permitiendo mejorar el control de existencias, agilizar el proceso de venta y facilitar la generación de reportes para la toma de decisiones.


# Resumen Ejecutivo

El Sistema de Gestión de Inventario para Mini Súper fue desarrollado como una solución informática para mejorar la administración de un pequeño negocio comercial. El proyecto surge debido a la necesidad de sustituir los registros manuales por un sistema que permita controlar el inventario, registrar ventas y administrar la información de productos y proveedores de forma eficiente.

La aplicación fue desarrollada utilizando **Java** como lenguaje de programación y **MySQL** como sistema gestor de bases de datos. Además, durante el desarrollo se aplicó la metodología **Scrum** para organizar el trabajo mediante Sprints, historias de usuario y seguimiento de actividades en GitHub.

El sistema permite registrar productos, categorías y proveedores, controlar entradas y salidas de mercancía, realizar ventas y generar reportes que apoyan la toma de decisiones del negocio.



# Descripción

El Sistema de Gestión de Inventario para Mini Súper es una aplicación diseñada para apoyar las operaciones diarias de un establecimiento comercial. Su objetivo principal es facilitar la administración del inventario mediante el registro y actualización de productos, el control de existencias y el procesamiento de ventas.

El sistema integra diferentes módulos que permiten mantener organizada la información del negocio, reducir errores en los registros y mejorar la eficiencia en las actividades administrativas.


# Problema identificado

El Mini Súper Los Tres Hermanos realizaba el control de inventario y las ventas de forma manual, lo que ocasionaba problemas como:

- Desconocimiento del inventario disponible.
- Pérdidas por productos sin registrar.
- Dificultad para identificar productos con bajo inventario.
- Retrasos durante el proceso de venta.
- Errores en el registro de mercancía.
- Falta de reportes para apoyar la toma de decisiones.
- Escaso control sobre proveedores y productos.


# Solución

Se desarrolló un Sistema de Gestión de Inventario que centraliza la información del Mini Súper en una única aplicación.

La solución permite:

- Administrar productos.
- Administrar categorías.
- Registrar proveedores.
- Controlar entradas y salidas de mercancía.
- Gestionar el inventario en tiempo real.
- Registrar ventas.
- Generar reportes administrativos.
- Reducir errores ocasionados por procesos manuales.

---

# Arquitectura

El Sistema de Gestión de Inventario para Mini Súper está desarrollado siguiendo una arquitectura por capas, con el objetivo de facilitar el mantenimiento, la escalabilidad y la organización del código.

La arquitectura del sistema se divide en los siguientes componentes:

- **Interfaz de Usuario:** Permite la interacción del usuario mediante las diferentes pantallas del sistema.
- **Lógica de Negocio:** Contiene las reglas de operación para la gestión de inventario, ventas, productos y proveedores.
- **Acceso a Datos:** Se encarga de la comunicación con la base de datos MySQL para almacenar y recuperar información.
- **Base de Datos:** MySQL almacena toda la información relacionada con productos, categorías, proveedores, inventario y ventas.

### Arquitectura General

```text
                Usuario
                   │
                   ▼
          Interfaz del Sistema
                   │
                   ▼
          Lógica de Negocio
                   │
                   ▼
          Acceso a Datos
                   │
                   ▼
              Base de Datos
                 (MySQL)
```

---

# Tabla de Contenidos

- [Resumen Ejecutivo](#resumen-ejecutivo)
- [Descripción](#descripción)
- [Problema identificado](#problema-identificado)
- [Solución](#solución)
- [Arquitectura](#arquitectura)
- [Requerimientos](#requerimientos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Uso](#uso)
- [Manual de Usuario](#manual-de-usuario)
- [Manual del Administrador](#manual-del-administrador)
- [Contribución](#contribución)
- [Roadmap](#roadmap)
- [Créditos](#créditos)
- [Licencia](#licencia)

---

# Requerimientos

## Software

- Java JDK 17 o superior.
- MySQL Server 8.0 o superior.
- Apache Maven.
- Git.
- GitHub.

## Herramientas de Desarrollo

- IntelliJ IDEA o NetBeans.
- MySQL Workbench.
- GitHub Desktop (opcional).

## Dependencias

- Java
- MySQL Connector
- Maven

## Sistema Operativo

Compatible con:

- Windows 10 o superior.
- Linux.
- macOS.
