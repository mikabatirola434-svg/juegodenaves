#  Juego de Naves en Consola — C++

**Proyecto:** Actividad 8 — Programación Orientada a Objetos (POO) en C++  
**Institución:** E.E.S.T. N.° 1 "Eduardo Ader" — Vicente López  
**Asignatura:** Laboratorio de Programación (LPR) — 5° Año  
**Autora:** Mikaela Batirola  
**Versión:** v1.0.0


##  Descripción

Este proyecto consiste en desarrollar un juego de combate espacial en consola utilizando C++. El jugador controla una nave, se mueve por la pantalla y dispara para destruir asteroides mientras intenta conservar sus vidas.

La actividad introduce la Programación Orientada a Objetos (POO) mediante clases, objetos, atributos privados, métodos públicos y constructores.

##  Controles

| Tecla | Función |
|---|---|
| W | Mover la nave hacia arriba |
| A | Mover la nave hacia la izquierda |
| S | Mover la nave hacia abajo |
| D | Mover la nave hacia la derecha |
| Espacio | Disparar |

##  Tecnologías utilizadas

- C++
- Biblioteca estándar de C++
- Windows API para controlar la posición del cursor en la consola
- Git y GitHub/GitLab para el control de versiones

##  Compilación y ejecución

Para compilar el programa, se necesita un compilador de C++ compatible con Windows, como MinGW.

Desde la carpeta principal del proyecto, ejecutar:

```bash
g++ -std=c++11 src/main.cpp -o src/juegodenaves.exe
```

Después, iniciar el juego con:

```powershell
.\src\juegodenaves.exe
```

##  Estructura del repositorio

```text
juegodenaves/
├── .gitattributes
├── .gitignore
├── LICENSE
├── README.md
├── docs/
│   ├── CHANGELOG.md
│   ├── InformeEEST1_LPR2026_ACT08_ApellidoNombre_v1.0.0.pdf
│   └── manuales/
│       ├── manual_programador_v1.0.0.pdf
│       └── manual_usuario_v1.0.0.pdf
├── src/
│   └── main.cpp
└── capturas/
    └── combate_consola.png
```

##  Documentación

La carpeta `docs/` contiene el informe académico en formato APA 7, el historial de versiones y los manuales del programador y del usuario.

La carpeta `capturas/` contiene las evidencias de ejecución del juego.

##  Objetivo de la actividad

Comprender los conceptos básicos de la Programación Orientada a Objetos, reconocer la diferencia entre `private` y `public`, trabajar con constructores y métodos, e implementar una funcionalidad adicional en el juego.

##  Estado del proyecto

Proyecto escolar en desarrollo correspondiente a la Actividad 8 de Laboratorio de Programación.