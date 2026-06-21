# Conclusiones y Recomendaciones del Proyecto

## Conclusiones

Durante este Sprint, la adopción de GitFlow junto con Conventional Commits permitió al equipo DeepLook mantener una organización clara del código fuente a lo largo del sprints, facilitando la trazabilidad de cambios y el trabajo paralelo entre los cinco integrantes.

El desarrollo incremental por sprints (Landing Page → Frontend → Backend) resultó efectivo para construir Impulso360 progresivamente, permitiendo validar cada capa antes de avanzar a la siguiente y evitando dependencias prematuras entre frontend y backend.

El despliegue evolucionó de forma coherente con la madurez del producto: GitHub Pages para la Landing Page estática, Firebase para el frontend Angular, y finalmente máquinas virtuales en Google Cloud Platform con separación de capas (aplicación y base de datos) para el backend en producción.

La aplicación de Domain-Driven Design y arquitectura hexagonal en el backend (bounded contexts de Agenda, Clients, Services, Profile, Notifications, Users) permitió organizar la lógica de negocio de manera modular, facilitando la documentación posterior mediante OpenAPI/Swagger.

Las entrevistas de validación con usuarios reales de ambos segmentos (microempresas de citas y emprendedores en digitalización) confirmaron que la propuesta de valor central — organización simple sin flujos de asistencia innecesarios es percibida positivamente y considerada útil para la gestión diaria del negocio.

La evaluación heurística reveló que, si bien la funcionalidad del sistema es sólida, existen brechas relevantes en consistencia visual y prevención de errores que no fueron detectadas durante el desarrollo, sino hasta la fase de auditoría UX.

Finalmente , los hallazgos de la evaluación heurística y de las entrevistas de validación constituyen un insumo clave para la siguiente entrega del proyecto, en la cual se espera subsanar las inconsistencias visuales, fortalecer las validaciones de los formularios y completar la internacionalización pendiente, consolidando así una versión de Impulso360 más robusta, accesible y alineada con los estándares de usabilidad esperados por ambos segmentos de usuarios.


## Recomendaciones

Con respecto a la gestión del equipo, es fundamental mejorar la organización interna mediante reuniones más frecuentes y una distribución de tareas más anticipada. Esto permitirá una mejor alineación de tiempos y criterios, evitando la presión de último momento y asegurando que las contribuciones individuales se integren correctamente para evitar conflictos en GitHub.

Asimismo, se recomienda medir la efectividad de los recordatorios (WhatsApp, SMS, Email) para optimizar los horarios y canales de envío según el comportamiento del usuario. Además de esta optimización técnica, es vital revisar la coherencia general del informe, asegurando que los diagramas, mockups y términos utilizados sigan una misma línea narrativa. Una revisión final colectiva de títulos, enlaces y redacción garantizará un producto más profesional y fácil de entender.

Definir como equipo un "Definition of Done" más estricto que incluya validaciones de UX/UI y de datos, no solo la entrega funcional del endpoint o vista. Esto evitaría que problemas de severidad alta (como la falta de validación en Clientes) lleguen hasta la fase de auditoría externa.

Realizar retrospectivas más profundas al cierre de cada sprint, donde el equipo discuta explícitamente hallazgos de consistencia y calidad (no solo velocity y story points completados), de modo que los aprendizajes de un sprint (ej. falta de i18n completa) se corrijan antes de replicarse en el siguiente.

Reforzar la revisión cruzada (code review) antes de marcar tareas como "Done". Varios problemas detectados en la evaluación heurística (botones inconsistentes, falta de validaciones, mezcla de idiomas) no fueron capturados durante el desarrollo, lo que sugiere que las Pull Requests se aprobaron sin una revisión visual/funcional rigurosa entre compañeros, más allá de la revisión técnica del código.