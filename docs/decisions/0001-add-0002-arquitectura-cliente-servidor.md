# ADD-0002-Arquitectura-Cliente-Servidor

* Status: proposed
* Date: 2023-10-16

## Context and Problem Statement

Se necesita una arquitectura de software para crear una aplicación web de gestión de proyectos que sea capaz de gestionar tareas, usuarios, y seguimiento del progreso del proyecto

## Decision Drivers

* RF01: La aplicación debe ser capaz de manejar un gran número de usuarios.
* RF02: La aplicación debe ser capaz de manejar diferentes tipos de servicios (tareas, usuarios, seguimiento).

## Considered Options

* ADD-0002.1-Arquitectura-Cliente-Servidor-MVC
* ADD-0002.2-Arquitectura-Cliente-Servidor-Capas

## Decision Outcome

Chosen option: "ADD-0002.1-Arquitectura-Cliente-Servidor-MVC", because Permite dividir el problema en diferentes componentes que pueden escalar y evolucionar independientemente. Cada componente puede ser desarrollado, desplegado y escalado de forma independiente. Además, el patrón MVC permite separar la lógica de negocio, la interfaz de usuario y el controlador

## Pros and Cons of the Options

### ADD-0002.1-Arquitectura-Cliente-Servidor-MVC

Se necesita una arquitectura de software para crear una aplicación web de gestión de proyectos que sea capaz de gestionar tareas, usuarios, y seguimiento del progreso del proyecto.

* Good, because permite la escalabilidad y la evolución independiente de cada componente.
* Good, because permite separar la lógica de negocio, la interfaz de usuario y el controlador.
* Bad, because introduce complejidad adicional en la gestión de los componentes y la comunicación entre ellos.
