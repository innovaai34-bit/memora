# MEMORA

**Sistema de gestión y memoria del conocimiento organizacional.**

Plataforma para capturar, organizar, validar, compartir y reutilizar el conocimiento que se produce en la experiencia diaria de los colaboradores de una organización.

Universidad Autónoma de Manizales · Manizales, Caldas · 2026

## Qué hace

- **Banco de conocimiento** — procedimientos, lecciones aprendidas y soluciones, con búsqueda y filtros por área, proceso, tipo, estado y palabras clave.
- **Compartir conocimiento** — formulario guiado por tipo de aporte, con palabras clave sugeridas, detección de posibles duplicados y confirmación obligatoria de confidencialidad.
- **Revisión y validación** — cola de validación con criterios, aprobación con nota y fecha de vigencia, solicitud de ajustes y archivo.
- **Indicadores** — los seis indicadores de la propuesta calculados en vivo sobre los aportes registrados.
- **Mapa de expertos** — quién ha documentado qué, cobertura por área y procesos sin conocimiento documentado.

## Sobre esta versión

Es una **demostración autónoma**: funciona sin servidor y guarda los datos en el `localStorage` del navegador de cada visitante, por lo que los aportes **no se comparten entre personas**. Trae nueve contenidos de ejemplo.

La versión completa corre sobre una base de datos compartida con control de acceso por rol (colaborador, validador, solo lectura) e incluye además consulta asistida por IA sobre el contenido aprobado, que requiere ese entorno.

## Ejecutar en local

Basta con abrir `index.html` en un navegador: no necesita instalación ni dependencias.
