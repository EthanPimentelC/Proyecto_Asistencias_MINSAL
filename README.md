# Proyecto_Asistencias_MINSAL
![Static Badge](https://img.shields.io/badge/python-%20?logo=python&labelColor=gray&color=yellow)
![Static Badge](https://img.shields.io/badge/flask-%20?logo=flask&labelColor=gray&color=oranage)
![Static Badge](https://img.shields.io/badge/jinja-%20?logo=jinja&logoColor=%237E0C1B&labelColor=gray&color=red)
![Static Badge](https://img.shields.io/badge/docker-%20?logo=docker&logoColor=%232496ED&labelColor=gray&color=blue)

## Equipo de desarrollo.
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Sady-Guzman">
        <img src="https://github.com/Sady-Guzman.png" width="100px;" alt="Sady-Guzman"/>
        <br />
        <sub><b>Sady Guzman</b></sub>
         <br />
        <sub><b>Jefe de proyecto</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/EthanPimentelC">
        <img src="https://github.com/EthanPimentelC.png" width="100px;" alt="EthanPimentelC"/>
        <br />
        <sub><b>Ethan Pimentel</b></sub>
         <br />
        <sub><b>Desarrollador</b></sub>
      </a>
    </td>
    <td align="center">
       <a href="https://github.com/danielestebanRA">
         <img src="https://github.com/danielestebanRA.png" width="100px;" alt="danielestebanRA"/>
         <br />
         <sub><b>Daniel Rojas</b></sub>
          <br />
         <sub><b>QA</b></sub>
       </a>
     </td>
  </tr>
</table>

## Problema a resolver

El sistema actual de marcaje y registro de horas trabajadas presenta múltiples problemas, especialmente en cuanto a la precisión del registro de turnos y horas trabajadas a lo largo del mes. Estos errores se ven amplificados por el gran volumen de trabajadores, lo que complica aún más el proceso de depuración de los datos de asistencia. Actualmente, esta depuración se realiza manualmente por el personal del área de Gestión de Personas, lo que supone una significativa inversión de tiempo.

## Propuesta

Se plantea una propuesta de software para optimizar el proceso de registro de asistencia que permita una integración eficiente con el Sistema de Información de Recursos Humanos (SIRH), reduciendo así errores y mejorando la eficiencia operativa. 
Detectando el mismo día del registro los marcajes duplicados, falta de marcaje de salida, entre otros.

---
### Carpetas:

* Documentación: Historial de propuestas, respuestas de clientes, diagramas, definiciones, y cartas Gantt de desarrollo y entregas en forma de PDF's.
* Templates: archivos HTML de las distintas páginas.
* static: Imagenes/iconos/logos.
* temp: Se usa durante el funcionamiento del sistema para guardar archivos temporales. Son eliminados al terminar la ejecución.
* horario_mensual: Directorio con volumen declarado en docker-compose. Se usa para guardar las reglas de horarios creados. Se actualiza cada mes.

## Prequisitos.
- Git.
- Docker.

## Instalación.
1. Clonar repositorio:
```
git clone https://github.com/EthanPimentelC/Proyecto_Asistencias_MINSAL.git
cd Proyecto_Asistencias_MINSAL
```
2. Ejecutar Docker (Asegurate de ejecutar docker primero).
```
docker compose up --build
```
