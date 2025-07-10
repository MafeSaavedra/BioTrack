\#Sistema de Registro y Mantenimiento de Dispositivos Médicos (BioTrack)



\##🧠 ¿Qué es?



\*\*BioTrack\*\* es una aplicación web especializada para técnicos biomédicos. Facilita el registro de fallas, la carga de evidencia fotográfica y el seguimiento detallado del mantenimiento de equipos médicos.  



Cada dispositivo cuenta con un historial individual y puede ser identificado rápidamente mediante un \*\*código QR único\*\*, permitiendo un acceso ágil desde cualquier navegador.



---



\##Público Objetivo



Este proyecto está dirigido a \*\*instituciones de salud ubicadas en la ciudad de Cúcuta\*\*, tales como:



\- Hospitales

\- Clínicas

\- Centros médicos

\- Entidades prestadoras de servicios de salud



El objetivo es brindarles una herramienta tecnológica que permita \*\*optimizar la gestión del mantenimiento de sus dispositivos médicos\*\*, facilitando:



\- El registro de fallas

\- El seguimiento técnico

\- La trazabilidad mediante código QR



---



\## 🛠️ Fase 1 – Versión de Escritorio (PC)



La primera fase del proyecto se enfocará en el desarrollo de una \*\*aplicación web accesible desde computador\*\*, ideal para el uso en áreas técnicas y administrativas dentro de las instituciones.  



\### Funcionalidades principales:



\- ✅ Registrar fallas o mantenimientos en tiempo real  

\- ✅ Consultar historial técnico por número de serie o nombre del equipo  

\- ✅ Subir evidencias fotográficas organizadas automáticamente  

\- ✅ Acceder a la información escaneando un código QR por dispositivo  



---



\## 🚀 Tecnologías Utilizadas



\### 🖥️ Frontend – React / Svelte

\- Interfaz intuitiva y responsiva, desarrollada con \*\*React\*\* o \*\*Svelte\*\*.

\- Permite a los técnicos biomédicos registrar eventos, consultar historial por equipo y visualizar evidencias.

\- Comunicación con el backend mediante peticiones HTTP usando \*\*fetch\*\* o \*\*axios\*\*.



\### ☁️ Backend – AWS Lambda + API Gateway (Node.js)

\- Arquitectura \*\*serverless\*\* construida con \*\*AWS Lambda\*\* en Node.js.

\- Expuesta a través de \*\*API Gateway\*\*, permitiendo manejar peticiones de forma escalable y eficiente sin servidores dedicados.

\- La combinación de React + Node.js es natural y altamente mantenible, ideal para desarrollos modernos en la nube.



\### 🗄️ Base de Datos – Amazon S3 (.json)

\- Los registros de fallas y mantenimiento se almacenan como archivos \*\*.json\*\* en \*\*Amazon S3\*\*.

\- Solución ligera, flexible y económica para manejar datos estructurados.



\### 📸 Evidencia Fotográfica – Amazon S3

\- Imágenes de fallas o mantenimientos almacenadas en \*\*S3\*\*, organizadas automáticamente por fecha y número de serie.

\- Facilita la trazabilidad, auditorías técnicas y generación de reportes.



\### 🔍 Extras – Escaneo de Código QR

\- Cada equipo cuenta con un código QR que, al ser escaneado desde cualquier navegador, permite acceder al historial técnico completo del dispositivo.

\- Mejora la rapidez en la toma de decisiones y el seguimiento técnico.



---



\## Diseños Preliminares

!\[BioTrack](./Design/BioTrack-D1.jpg)



