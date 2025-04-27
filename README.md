# Sistema de Gestión de Torneos de eSports

## Autor
Marcos González Sánchez
https://github.com/mgonzale42

## Descripción del Proyecto

https://github.com/mgonzale42/torneo-esports-uml.git

Este proyecto implementa un sistema de gestión de torneos de eSports
utilizando UML para el modelado y Java para la implementación.

## Diagramas UML
### Diagrama de Casos de Uso
![Diagrama de casos de uso](diagrams/casos-uso.png)

### Diagrama de Clases
![Diagrama de clases](diagrams/clases.png)

## Estructura del Proyecto

torneo-esports-uml/
├── src/ # Código fuente
│ ├── es/empresa/torneo/ # Paquete base del proyecto
│ │ ├── modelo/ # Clases de entidad
│ │ ├── control/ # Clases de control
│ │ ├── vista/ # Clases de interfaz (UI o consola)
│ │ ├── Main.java # Punto de entrada del programa
├── diagrams/ # Diagramas UML
│ ├── casos-uso.png # Diagrama de casos de uso
│ ├── clases.png # Diagrama de clases
├── README.md # Documentación del proyecto
├── .gitignore # Ignorar archivos innecesarios
├── LICENSE (opcional) # Licencia del proyecto

or

├── src/
│   └── es/
│       └── empresa/
│           └── torneo/
│               ├── modelo/
│               ├── control/
│               ├── vista/
│               └── Main.java
├── diagrams/
│   ├── casos-uso.png
│   └── clases.png
├── README.md
├── .gitignore
└── LICENSE (opcional)

## Instalación y Ejecución
1. Clonar el repositorio:
`git clone https://github.com/mgonzale42/torneo-esports-uml.git`

3. Compilar y ejecutar el proyecto:
`cd src javac es/empresa/torneo/Main.java java es.empresa.torneo.Main`

## Justificación del diseño
Por qué se eligió esa estructura y cómo se organizan las clases.

## Conclusiones
Sobre el aprendizaje obtenido.
