# Proyecto final de Ingeniería de Software
Nuestro proyecto trata de una aplicación web para que alumnxs del ITAM busquen, agenden y ofrezcan asesorías. 

## Índice
- [Objetivo del proyecto](https://github.com/chimchars/ingsoft#Objetivo-del-proyecto)
- [Integrantes del equipo](https://github.com/chimchars/ingsoft#Integrantes-del-equipo)
- [Plan de calidad de software (SQA)](https://github.com/chimchars/ingsoft#Plan-de-calidad-de-software-sqa)
- [Roadmap](https://github.com/chimchars/ingsoft#Roadmap)
- [Requerimientos](https://github.com/chimchars/ingsoft#Requerimientos)
- [Casos de uso](https://github.com/chimchars/ingsoft#Casos-de-uso)
- [Costos](https://github.com/chimchars/ingsoft#Costos)
- [Avances](https://github.com/chimchars/ingsoft#Avances)

## Objetivo del proyecto 
Crear una aplicación web funcional que permita que alumnxs itamitas ingresen con sus clave única para buscar, agendar y ofrecer asesorías.  La aplicación también permitirá que administración del ITAM entre a la página para registrar las instalaciones institucionales en donde se podrán llevar a cabo dichas asesorías, y que lxs alumnxs puedan calificar las asesorías después de tomarlas.

## Integrantes del equipo:
- [Santiago](https://github.com/chimchars/ingsoft#Santiago-Moreno-Rojas)
- [Alonso](https://github.com/chimchars/ingsoft#Alonso-Barroso-Corral)
- [Sebastián](https://github.com/chimchars/ingsoft#Sebastián-Luis-González-Hacker)

### Santiago Moreno Rojas 
Estudiante de ingeniería en computación. Le gusta leer y estar con sus amigxs.

### Alonso Barroso Corral
Estudiante de ingeniería en computación.

### Sebastián Luis González Hacker
Estudiante de ing. en computación e ing. en negocios. Fuerte interés en tecnología financiera.

## Plan de calidad de software (SQA)
### Funcionalidad
Refinamiento de casos de uso para prevenir la ocurrencia de casos imprevistos. Más detalles al roadmap.
### Confiabilidad
Pruebas de estresamiento del sistema. 
### Usabilidad
Uso de prototipos de baja y alta fidelidad para probar la usabilidad del sistema. 
### Eficiencia
Tests automatizados e implementar controles de calidad desde un principio.
### Mantenibilidad
Revisión de código por pares. Debe existir una cantidad de comentarios que evidencie lo que hace el programa para alguien que no lo escribió.
### Portabilidad 
Front: ReactJS y Tailwind; back: Express; base de datos: MySQL; auth: JWT; orm: Prisma.
### Documentación 
Además de la documentación constante del código, habrá documentación en GitHub detallando la organización y construcción del proyecto.

## Roadmap
![alt text](https://github.com/chimchars/ingsoft/blob/main/readmeImgs/roadmap.png)

## Requerimientos
### De Negocio 
Lograr una aplicación que permita que alumnxs del ITAM ofrezcan, anuncien, agenden y califiquen asesorías en el ITAM. 
### Técnicos
### Funcionales
Aplicación web, accesible dentro de cualquier browser, que contenga:
- Página principal
- Interfaz de inicio de sesión
- Barra de navegación para dar/buscar asesorías
- Interfaz para añadir funcionalidades de persona asesora:
  - Qué materias quiere enseñar, qué materias correspondientes llevó, cómo le fue en ellas, si quiere cobrar o no, horario
- Interfaz para añadir funcionalidades Estudiante 
  - En qué materias tiene dudas
- Interfaz de registro para crear cuenta estudiantil
- Interfaz de registro para crear cuenta administrativa
- Interfaz de búsqueda de asesorías con filtros (materias, horario, presencial o virtual, costo máximo)
- Base de datos
- Interfaz de pago
La aplicación debe cumplir los estándares estipulados en el SQA previamente.


## Casos de uso
![Captura de Pantalla 2022-11-18 a la(s) 7 20 08 a m](https://user-images.githubusercontent.com/47926338/202714492-991d4b3b-e445-4e6a-8d7f-0155f905930d.png)

## Costos
Calculamos los costos del proyecto en [este documento.](https://docs.google.com/spreadsheets/d/1VyvFcyO7h51ESQJbOq1LToGsr4ErrPnfKpyfbs28pO0/edit?usp=sharing)

## Otros repositorios necesitados
- Los separamos para facilitar el CI/CD que se va a implementar

#### [Frontend](https://github.com/alonsobarrosoc/IngSoftFront)

#### [Backend](https://github.com/alonsobarrosoc/IngSoftBack)

## Avances
### Frontend (main branch)
https://asesorias-itam.netlify.app/
### Backend (main branch)
https://ingsoft-asesorias.herokuapp.com/
### Postman collection and enviroment
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/47ffb54a75d34be27911?action=collection%2Fimport#?env%5BIngSoftv1%5D=W3sia2V5IjoiYmFzZVVybCIsInZhbHVlIjoiaHR0cHM6Ly9pbmdzb2Z0LWFzZXNvcmlhcy5oZXJva3VhcHAuY29tL2FwaSIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiaHR0cHM6Ly9pbmdzb2Z0LWFzZXNvcmlhcy5oZXJva3VhcHAuY29tL2FwaSIsInNlc3Npb25JbmRleCI6MH1d)





