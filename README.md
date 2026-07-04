# Formulario-Iniciativa-IA

Formulario institucional desarrollado en **Power Apps**, destinado a registrar, gestionar y evaluar propuestas relacionadas con **Inteligencia Artificial** y soluciones basadas en **Microsoft Power Platform**.

<p align="center">
  <img src="Inicio IA.png" width="100%" />
</p>

## 🚀 ¿Qué realiza el sistema?

El sistema permite a los colaboradores registrar iniciativas de innovación tecnológica de forma centralizada, facilitando su evaluación y seguimiento por parte del equipo responsable.

### Funcionalidades implementadas

- Autenticación automática mediante Microsoft 365 (User365), identificando al usuario sin necesidad de ingresar credenciales adicionales.
- Registro de iniciativas mediante un formulario institucional.
- Carga de documentos de respaldo mediante archivos adjuntos.
- Registro automático de información administrativa:
  - Año.
  - Semestre.
  - Fecha de creación.
- Almacenamiento de toda la información en la lista **Ficha Iniciativa IA** de SharePoint.
- Flujo de revisión para evaluadores, incluyendo:
  - Estado de revisión.
  - Fecha de revisión.
  - Responsable de la revisión.
  - Nota de evaluación.
  - Observaciones.

### Información ingresada por el usuario

- Nombre del responsable.
- Nombre de la iniciativa.
- Área.
- Eslabón estratégico.
- Pilar estratégico.
- Archivo adjunto.

### Validaciones implementadas

- No permite registrar más de una iniciativa por responsable.
- Si el responsable ya posee un registro, se muestra el siguiente mensaje:

> **"Ha alcanzado el límite, ya se envió un registro con el nombre de responsable. Ante cualquier consulta, puede contactar a Rodrigo Villalobos, Benito Serrano o Sebastián Carreño."**

- Validación de todos los campos obligatorios antes del envío.
- No permite guardar registros con información incompleta.

## 📄 Documentación

La visualización del sistema se encuentra disponible en el siguiente archivo:

- **Iniciativa IA_PB.pdf**

