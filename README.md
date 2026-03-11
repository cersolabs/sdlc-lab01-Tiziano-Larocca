[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-s1_zvqh)
# SDLC-Lab01

- Requisitos de entrega y aprobacion:
  - Respetar el formato Markdown.
  - Solo se aceptan los trabajos por GitHub Classroom
  - Todas las respuestas deben realizarse en el archivo **README.md** del repositorio asignado..
  - El Trabajo en individual. Si bien se puede realizar de forma grupal, la entrega es siempre ***individual***
  - Defensa individual
  - Respetar las fechas de entraga. No se aceptan las actividades fuera de termino.

> Si surge algún cambio o aclaración adicional, se comunicará durante la clase.

### Actividad 1
Teniendo en cuenta el material de clase, responda las siguientes preguntas:

1. ¿Por qué el desarrollo de software no puede realizarse simplemente comenzando a programar?

   R: Un proyecto de desarrollo de software no puede realizarse comenzando a programar. Un desarrollo de software requiere de planificación, debe cumplir con ciertas pautas / requerimientos en un orden, además,
   antes del código es necesario definir el diseño de la arquitectura del sistema. Durante la implementación del código tambien es necesario ir testeando el programa para asegurarse de que cumple con lo requerido.
   Es todo un proceso que se desarrolla en etapas (requerimientos, diseño del sistema, implementación / código, testing, despliegue y mantenimiento).

2. ¿Qué significa que un desarrollo sea dirigido por un plan?

   R: Que un desarrollo este dirigido por un plan significa que el proyecto se está realizando con una planificación donde se definen con anticipación los requerimientos del sistema, las etapas del desarrollo, los            tiempos, los recursos que se usarán, etc. 

3. ¿Cuáles son las ventajas de utilizar un plan de desarrollo?

   R: Algunas ventajas de utilizar un plan de desarrollo son:
     - Se pueden presupuestar costos
     - Estimar los tiempos de desarrollo
     - Etapas ya definidas
     - Los requisitos planteados entre el cliente y el desarrollador podrán verse en el despliegue del software
     - Definir recursos a usar

4. ¿Qué críticas se hacen a los modelos tradicionales de desarrollo?

   R: Los modelos tradicionales hoy en día rara vez se usan, hoy se prefieren usar métodos ágiles de desarrollo. En los modelos tradicionales hay poca interacción con los clientes, los errores de una etapa se arrastran a
   etapas posteriores y los requerimientos deben definirse al inicio con los menores cambios posibles. Un cambio en los requerimientos puede afectar significativamente a un software con un desarrollo alto.

5. ¿Por qué en la práctica muchas organizaciones combinan metodologías ágiles y modelos dirigidos por un plan?

   R: Muchas organizaciones combinan metodologías porque cada una tiene sus ventajas distintas y se complementan entre sí. Por ejemplo, los modelos dirigidos por un plan serán más organizados definiendo costos, tiempos,
   etapas, requisitos, etc. Y por otro lado la metodología ágil permite que el software se desarrolle de manera incremental, adaptandose rápidamente a cambios y mejorando el software.
   En resumen, las organizaciones utilizan planes de desarrollo para definir el diseño general del proyecto y luego aplican prácticas ágiles para desarrollarlo de la manera más rapida y eficiente, adaptandose a cambios.


### Actividad 2

| Etapa                         | Descripción |
|--------------------------------|-------------|
| Análisis                      | Etapa inicial. Los analistas entrevistan a los clientes para identificar sus necesidades y los problemas que habrá en el sistema. Se definen los requerimientos del cliente y las limitaciones o restricciones. |
| Diseño                        | Se elabora el diseño del software abordando los problemas identificados. Se cumplen los requerimientos establecidos y se respetan las limitaciones. Esto genera documentación técnica que permite a los programadores construir el código de mejor manera. |
| Codificación                  | Los programadores construyen el programa acorde al diseño establecido, utilizando un lenguaje de programación determinado. |
| Prueba                        | Se testea el sistema para detectar errores y corregirlos. Además, se evalúa si el programa cumple con los requerimientos del cliente. |
| Puesta en marcha / Despliegue | Se instala o lanza el software para el cliente en su computadora y se capacita a los usuarios para que utilicen el programa correctamente. |


* Luego responda:
  * ¿En qué etapa se obtienen los requerimientos del sistema?
    
    R: Los requerimientos del sistema se obtienen en la primera etapa, la de análisis de requerimientos.
  * ¿En qué etapa se construye el programa?

    R: El programa se construye en la etapa de codificación.
  * ¿Cuál es el objetivo principal de las pruebas?
    
    R: El objetivo principal de las pruebas es detectar errores en el programa para corregirlo.
### Actividad 3
Ordene las siguientes etapas según corresponda  Diseño
-al modelo lineal secuencial:
- Codificación
- Prueba
- Diseño
- Despliegue
- Ingeniería de requerimientos
---
R: 
- Ingeniería de requerimientos
- Diseño
- Codificación
- Prueba
- Despliegue

- Luego responder:
  * ¿Qué problema puede surgir si hay un error en una etapa inicial?
    
    R: Si hay un error en la etapa de análisis de requerimientos, pueden surgir problemas como un rediseño del programa, retrasos, cambio sn la codificación, aumento de costos y tiempos y un programa que no cumple con las nececisades del cliente.
  * ¿Por qué este modelo puede ser problemático cuando los requerimientos cambian?

    R: Cuando los requerimientos cambian, este modelo es problemático porque se deben volver a ver etapas anteriores, lo que provoca un resideño del software, un nuevo código, más tiempo y más costos.
### Actividad 4
Complete la siguiente tabla.
| Modelo      | Característica principal | Cuándo conviene usarlo |
| ----------- | ------------------------ | ---------------------- |
| Cascada     | Sistema que consta de 5 etapas las cuales se completan de forma lineal, modelo clásico.                         | Conveniente usar en programas pequeños y simples, proyectos sencillos.                       |
| Incremental | Se entregan versiones tempranas o "demos" al cliente, sistemas completos y operables. Conforme avancen las versiones se agregan más funcionalidades segun lo que el cliente requiera.                       | Conveniente usar cuando el proyecto es algo más grande y dispone de mayores riesgos. Es mejor entregar algo pequeño al principio para luego mejorarlo con el tiempo y llegar a su versión final.                        | 
| Prototipos  | Versiones tempranas no funcionales del programa. Se utiliza para que el usuario visualice lo que se está planificando hacer. Una vez el prototipo es aprobado, este se desecha y se empieza con el programa real.                          | Conveniente usar en programas donde los requerimientos no están del todo claros, y donde se desee reducir los riesgos de un sistema que no cumpla con lo que un cliente espera.                      |
| Espiral     | A las etapas habituales del proyecto se le agrega una nueva llamada "análisis de riesgo", donde a partir de estos análisis el programa se modifica. Las primeras etapas constan de prototipos para luego pasar a una versión operativa hasta completar el programa. Esta etapa se encuentra luego del diseño.                        | Conveniente usar en desarrollos muy riesgosos y algo grandes.                       |
| RAD         | Los desarrolladores usan herramientas que les permite generar código con rapidez, usan componentes ya predefinidos o reusables. Además, el desarrollo de la aplicación se divide en equipos que trabajan de forma concurrente.                        | Conviene usar cuando el proyecto no es grande y se tienen claros los requerimientos del cliente o también acotar tiempos.                       |

- Responder:
  - ¿Qué modelo es más adecuado cuando existen muchos riesgos en el proyecto?
    
    R: El modelo espiral
    
  - ¿Qué modelo ayuda a comprender mejor los requerimientos del usuario?
    
### Actividad 5 – Caso práctico
Una empresa quiere desarrollar un sistema de ventas para un pequeño comercio.

**Características del proyecto:**
- Sistema relativamente pequeño
- Pocos usuarios
- Requerimientos claros
- Tiempo limitado

**Preguntas**

- ¿Qué modelo de desarrollo recomendaría? 

  R: 
- Justifique su respuesta.

  R:
- ¿Qué etapas principales tendría el desarrollo?

  R:

### Actividad 7 – Verdadero o Falso
Indique si las siguientes afirmaciones son Verdaderas (V) o Falsas (F). ***marcar con x la verdaderas, dejar en blanco las falsas***

1. [ ] El modelo en cascada permite cambios constantes en los requerimientos.
2. [ ] El modelo incremental entrega el sistema en varias versiones.
3. [ ] Un prototipo se utiliza para comprender mejor los requerimientos.
4. [ ] El modelo RAD busca reducir los tiempos de desarrollo.
5. [ ] El modelo en espiral incorpora el análisis de riesgos.
