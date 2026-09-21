# 🎾 Padel Analyzer PRO - AI Sport Coaching (System Architecture & PRD)

![Status: System Design](https://img.shields.io/badge/Status-System_Design_%26_Architecture-blue)
![Role: Project Lead](https://img.shields.io/badge/Role-Project_Lead-success)
![Tech: MediaPipe AI](https://img.shields.io/badge/Tech-Google_MediaPipe-orange)

> **💡 Nota del repositorio:** Este repositorio contiene el **Product Requirements Document (PRD)** y el diseño de arquitectura completo (83 páginas) para una aplicación de análisis deportivo impulsada por Inteligencia Artificial. No incluye código fuente, sino la planificación integral del ciclo de vida del software, diseño UI/UX, modelado de base de datos y estrategia de despliegue.

## 🚀 Visión del Producto
**Padel Analyzer PRO** nace con el objetivo de democratizar el entrenamiento deportivo de élite. Utilizando visión por computadora, la aplicación actúa como un "entrenador en el bolsillo", capaz de leer los movimientos del jugador frame a frame, generar esqueletos virtuales, analizar la técnica de golpeo y ofrecer *feedback* biomecánico inmediato y personalizado.

---

## 🧠 Arquitectura Conceptual y Tecnologías Core

Aunque en fase de diseño, la arquitectura del sistema está planteada sobre tecnologías robustas para garantizar escalabilidad (multideporte) y precisión:

*   **Motor de Inteligencia Artificial:** Integración de **Google MediaPipe** para la estimación de posturas. Mapeo de 33 *keypoints* (puntos clave) para calcular ángulos articulares (codo, torso, muñeca), distancias relativas y tiempos de reacción.
*   **Diseño de Base de Datos:** Arquitectura relacional para vincular la telemetría del jugador con el contenido educativo (entidades: `Vídeo`, `Nivel`, `Movimiento` e interrelaciones N:M).
*   **Gestión del Proyecto:** Metodología Agile con diagramas de Gantt planificados y ejecutados íntegramente en **Jira**.

---

## 📱 Interfaz y Experiencia de Usuario (UI/UX)

El diseño prioriza la fluidez y la retención del usuario mediante un bucle de *Gamificación y Mejora Continua*:

*(Añade aquí una captura de pantalla del PDF donde se vean los móviles con la interfaz, como la pantalla de "Métricas del partido" o "Análisis de Técnica")*
`![UI Mockup](ruta-de-tu-imagen1.png)`

*   **Zonas de Impacto y Heatmaps:** Visualización de la actividad en pista y consistencia de golpeo.
*   **Reproductor Interactivo:** *Feedback* visual superpuesto al vídeo real del jugador indicando errores de postura.
*   **Smart Library:** Sistema de recomendación que cruza los errores detectados por la IA con vídeos formativos específicos para corregirlos.

---

## 🎯 Mi Rol en el Proyecto: Project Lead / Coordinador

En este proyecto asumí el rol de **Líder y Coordinador** de un equipo de 5 personas. Mis responsabilidades clave incluyeron:

1.  **Definición de Producto:** Establecer la visión, las mecánicas de gamificación y los parámetros técnicos que la IA debía medir (tiempos de reacción, ángulos de pala).
2.  **Gestión del Ciclo de Vida:** Supervisión y control de avance, desde la fase de ideación inicial hasta el despliegue del *Minimum Viable Product* (MVP).
3.  **Control de Calidad (QA):** Establecimiento de los umbrales de éxito (precisión del modelo IA > 90%).
4.  **Toma de Decisiones y Mitigación de Riesgos:** Elaboración de planes de contingencia frente a posibles desviaciones de tiempo, falsos positivos de la IA o cuellos de botella en la renderización móvil.

*(Añade aquí una captura de pantalla del Diagrama de Jira o de la Base de Datos del PDF)*
`![Arquitectura y Gantt](ruta-de-tu-imagen2.png)`

---

## 📂 Documentación Completa

El documento íntegro incluye diagramas de flujo de usuarios, estudios de mercado, roles del equipo, análisis de *Stakeholders* y la estrategia comercial GTM (Go-To-Market).

👉 **[Haz clic aquí para leer el Documento de Arquitectura y Diseño Completo (PDF)](Enlace-a-tu-pdf-subido.pdf)**
