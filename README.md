# Asistente de Seguridad – MIDTECH

Este repositorio contiene el desarrollo de un asistente de seguridad orientado al análisis de políticas de seguridad de la información, detección de incumplimientos normativos y generación de propuestas de mejora basadas en estándares como GDPR e ISO 27001.

El proyecto ha sido desarrollado como parte de un trabajo académico, utilizando principalmente n8n como herramienta de orquestación, sin necesidad de desarrollo tradicional.

---

## Contenido del repositorio

En este repositorio se puede encontrar:

- **Documentación del proyecto**
- **Workflow en formato JSON utilizado en n8n**

---

## Documentación del proyecto

La carpeta de documentación incluye todo el proceso de desarrollo del sistema, desde su concepción inicial hasta la versión final.

En ella se detalla:

### Inicio del proyecto
Cómo se definió la idea del asistente, los objetivos iniciales y el enfoque general.

### Fases de desarrollo
Evolución del proyecto a través de distintas iteraciones, incluyendo cambios de enfoque, rediseños de workflows y mejoras progresivas.

### Problemas y errores
Dificultades encontradas durante el uso de n8n, errores en la lógica de los flujos y soluciones aplicadas mediante prueba y error.

### Versión final
Descripción del resultado final del asistente y su funcionamiento completo.

---

## Enlaces importantes

En la documentacion tambien se pueden encontrar enlaces importantes como:
- Carpeta de documentación: *(añadir enlace aquí)*
- Vídeo demostración: *(añadir enlace aquí)*
- Repositorio GitHub: *(este mismo repositorio)*

---

## Workflow de n8n

Este repositorio incluye el archivo JSON del workflow utilizado en n8n.

Este workflow implementa la lógica principal del asistente:

- Procesamiento de documentos (PDF)
- Análisis de políticas de seguridad
- Detección de incumplimientos normativos
- Comparación con GDPR e ISO 27001
- Generación de respuestas estructuradas
- Propuestas de mejora

El diseño se ha realizado completamente en n8n, priorizando una arquitectura modular y fácilmente modificable.

![Texto alternativo para la imagen](https://github.com/Ex-1232/TFC---1232/blob/main/Diagrama%20de%20flujo)

---

## Enfoque del proyecto

El desarrollo se ha basado en un proceso iterativo:

- Construcción inicial de workflows básicos
- Pruebas y detección de errores
- Replanteamiento de soluciones
- Mejora progresiva del sistema

El uso de n8n ha supuesto un reto importante, especialmente al no tener experiencia previa, lo que ha obligado a aprender mediante experimentación constante, prueba y error.

---

## Mejoras futuras

Una de las principales mejoras identificadas es la optimización del procesamiento de documentos.

Actualmente, el sistema reprocesa todos los archivos en cada ejecución. Para optimizarlo se propone:

- Implementar detección de documentos ya procesados (hash o ID único)
- Evitar duplicados en Supabase
- Reducir tiempos de ejecución
- Mejorar eficiencia del flujo completo

---

## Conclusión

Este proyecto ha permitido construir un asistente funcional de análisis de seguridad, al mismo tiempo que ha supuesto una experiencia práctica en automatización, diseño de flujos y resolución de problemas reales.

El resultado final es un sistema capaz de analizar políticas de seguridad, detectar incumplimientos normativos y proponer mejoras alineadas con estándares internacionales.
