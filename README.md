# MPAZPRO

**Aplicación móvil de apoyo didáctico y seguimiento del aprendizaje**

Proyecto académico de la asignatura **DSY1105 - Desarrollo de Aplicaciones Móviles**, desarrollado en el contexto de la Escuela Escritora Marcela Paz, San Bernardo.

## 1. Descripción del proyecto

MPAZ PRO es una propuesta de aplicación móvil educativa orientada a estudiantes de Tercero Básico. Su propósito es complementar el trabajo pedagógico mediante contenidos, actividades, desafíos y evaluaciones organizados por asignatura y objetivo de aprendizaje.

La aplicación contempla funcionalidades diferenciadas para estudiantes y docentes, junto con mecanismos de registro del progreso y consulta de resultados.

El proyecto corresponde a un producto mínimo viable (MVP) académico y no constituye una plataforma educativa de producción.

## 2. Objetivos

- Organizar contenidos educativos por asignatura, unidad y objetivo de aprendizaje.
- Facilitar la realización de actividades y desafíos progresivos.
- Proporcionar retroalimentación sobre las respuestas de los estudiantes.
- Registrar el avance y los resultados mediante almacenamiento local.
- Facilitar al docente la revisión de resultados e información de seguimiento.
- Aplicar principios de usabilidad, modularidad y separación de responsabilidades.

## 3. Tecnologías

Tecnologías previstas para el desarrollo:

- Kotlin.
- Android Studio.
- Jetpack Compose.
- Material Design 3.
- Arquitectura MVVM.
- ViewModel y StateFlow.
- Room para almacenamiento local.
- Git y GitHub para control de versiones.


## 4. Perfiles de usuario

### Estudiante

- Consultar contenidos asignados.
- Desarrollar actividades y desafíos.
- Responder evaluaciones.
- Revisar respuestas correctas e incorrectas.
- Consultar su progreso.

El perfil estudiante no puede modificar contenidos pedagógicos ni consultar informes reservados al docente.

### Docente

- Consultar objetivos de aprendizaje disponibles.
- Seleccionar y asignar contenidos y actividades.
- Configurar el máximo de intentos de las evaluaciones.
- Revisar resultados y avances.
- Consultar y validar informes pedagógicos.

La validación de los informes corresponde a una revisión profesional y no se sustituye por decisiones automatizadas de la aplicación.

## 5. Alcance del MVP

La aplicación considera como máximo una unidad por cada una de las siguientes asignaturas:

1. Lenguaje y Comunicación.
2. Matemática.
3. Ciencias Naturales.
4. Historia, Geografía y Ciencias Sociales.

Los contenidos y datos utilizados serán ficticios o procederán de fuentes públicas o autorizadas.

No se utilizarán datos personales reales de estudiantes ni se realizarán conexiones con sistemas institucionales.

## 6. Funcionalidades previstas

- Navegación entre pantallas.
- Selección de asignaturas y unidades.
- Visualización de contenidos y ejemplos.
- Actividades y desafíos progresivos.
- Evaluaciones con alternativas e intentos limitados.
- Validación de formularios y retroalimentación visual.
- Registro local de respuestas y progreso.
- Consulta de resultados por el perfil docente.
- Recursos nativos del dispositivo.
- Animaciones y transiciones visuales.
- Persistencia local de los datos.

**Estado del proyecto:** desarrollo inicial. Las funcionalidades se marcarán como implementadas y verificadas a medida que se desarrollen y prueben.

## 7. Arquitectura del proyecto

Se utilizará una arquitectura MVVM con separación de responsabilidades:

- **Model:** representa los datos y las entidades del dominio.
- **ViewModel:** administra el estado de la interfaz y coordina la lógica de presentación.
- **Repository:** centraliza el acceso y las operaciones sobre los datos.
- **Data/Local:** contiene los componentes de persistencia local.
- **UI/Screens:** contiene las pantallas de la aplicación.
- **UI/Components:** agrupa componentes visuales reutilizables.
- **Navigation:** administra las rutas y la navegación.

La estructura definitiva se documentará conforme a la implementación real.

## 8. Almacenamiento local

Se contempla utilizar Room para almacenar datos ficticios relacionados con usuarios, contenidos, actividades, respuestas, intentos y progreso.

La implementación deberá permitir registrar, consultar y actualizar información, conservando el progreso después de cerrar y volver a abrir la aplicación.

## 9. Recursos nativos

Se contempla integrar recursos nativos de Android, como:

- Selección de imágenes mediante el selector de fotos del sistema.
- Reproducción de audio para apoyar las explicaciones educativas.

Estos recursos se considerarán implementados únicamente cuando funcionen dentro de la aplicación y se hayan verificado.

## 10. Requisitos de ejecución

Para ejecutar el proyecto se necesitará:

- Android Studio.
- JDK compatible con la versión de Gradle utilizada.
- Android SDK y herramientas de compilación correspondientes.
- Emulador Android o dispositivo físico compatible.

Las instrucciones específicas se completarán cuando se haya configurado y probado el proyecto.

## 11. Instalación y ejecución

1. Clonar el repositorio.
2. Abrir la carpeta raíz del proyecto en Android Studio.
3. Esperar a que finalice la sincronización de Gradle.
4. Configurar un emulador Android o conectar un dispositivo compatible.
5. Ejecutar la configuración `app` mediante la opción Run.

Si aparecen errores de configuración o compilación, revisar las versiones de Gradle, Kotlin, Android Gradle Plugin y Android SDK.

## 12. Pruebas

Se deberán verificar, como mínimo:

- Navegación entre pantallas.
- Validaciones de formularios.
- Registro y recuperación del progreso.
- Cálculo de resultados e intentos permitidos.
- Separación de las funciones de estudiante y docente.
- Funcionamiento de los recursos nativos.
- Actualización de la interfaz ante cambios de estado.

Los resultados de las pruebas se documentarán después de su ejecución.

## 13. Privacidad y restricciones

- Todos los usuarios y resultados serán ficticios.
- No se incorporarán credenciales ni secretos al repositorio.
- El informe pedagógico estará reservado al perfil docente.
- No se conectarán sistemas institucionales reales.
- La aplicación no emitirá diagnósticos ni decisiones académicas automáticas.
- Los contenidos respetarán las condiciones de uso de sus fuentes.

## 14. Organización del trabajo

El desarrollo se organizará en las siguientes etapas:

1. Configuración del proyecto y estructura MVVM.
2. Diseño visual y navegación.
3. Implementación de perfiles y funcionalidades.
4. Formularios y validaciones.
5. Persistencia local.
6. Recursos nativos y animaciones.
7. Pruebas, correcciones y documentación.
8. Preparación de la defensa técnica.

La distribución de tareas y los avances se registrarán en la herramienta de planificación del equipo.

## 15. Equipo

- Integrante 1: Josefa Lagos.
- Integrante 2: Cristóbal Ruiz.

## 16. Contexto académico

- **Asignatura:** DSY1105 - Desarrollo de Aplicaciones Móviles.
- **Proyecto:** MPAZ PRO.
- **Institución:** Duoc UC.
- **Caso:** Escuela Escritora Marcela Paz.

---

**Nota:** este documento describe el alcance y la planificación del proyecto. Los apartados sobre funcionalidades implementadas, versiones, pruebas y ejecución deberán actualizarse para reflejar el estado real del código.
